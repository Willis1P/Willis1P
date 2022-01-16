const express = require('express')
const app = express()

const webDeveloper = {name:"Willis", stack:"Full-Stack-Developer"}

app.get('/', (req, res) =>{
  return res.send(webDeveloper)
}),

app.listen(3000, () =>{
  console.log("Initing code...")
})
