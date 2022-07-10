const express = require('express')

const app = express()

app.use(express.static(__dirname + '/static/dist'))

app.get('/sort', (request, response) => {
    response.send({ name: 'cgl' })
})

app.listen(5000, (err) => {
    if (!err) console.log('服务器启动成功了')
})