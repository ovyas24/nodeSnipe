# Nodejs Snippites Extensions

 A simple small extension for most use code blocks in node-express app

## Code Blocks

#### key-word __!node__ : *Adds a Simple Node and express template*

#### Code added

```js

 const express = require('express')
 const app = express()
 const port = process.env.PORT||3000
 
 app.get('/',(req,res)=>{
    res.send('http-response)')
 })
 
 app.listen(port,(req,res)=> console.log(`App running at port port`))

```

#### key-word **!ex-stat** : *Adds a static file location in app*

#### Code added

```js
app.use(express.static('public'))
```

#### key-word **!ex-router** : *Template for a route page*

#### Code added

```js
const express = require('express')
const router = express.Router()

router.get('/',(req,res)=>{
   res.send(http-response)
})

module.exports = router
```