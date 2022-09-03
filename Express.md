>Express is a minimal and flexible Node.js web application framework
# express()
* Creates an Express application. The express() function is a **top-level function** exported by the express module.
```
const express = require('express')
const app = express()
```
# Application
* The app object conventionally denotes the **Express application**. Create it by calling the top-level express() function exported by the Express module:
```
const express = require('express')
const app = express()

app.get('/', (req, res) => {
  res.send('hello world')
})

app.listen(3000)
```
## app.use([path,] callback [, callback...])
  * path defaults to “/”
