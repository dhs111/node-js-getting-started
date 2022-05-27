const express = require('express')
const path = require('path')
const PORT = process.env.PORT || 5000

	app.get('/bc.jpg', function (req, res) {
		res.sendFile(__dirname + '/bc.jpg');          
	})

express()
  .use(express.static(path.join(__dirname, 'public')))
  .set('views', path.join(__dirname, 'views'))
  .set('view engine', 'ejs')
  .get('/', (req, res) => res.render('pages/index2'))

  .listen(PORT, () => console.log(`Listening on ${ PORT }`))

