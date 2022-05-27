/*
const express = require('express')
const path = require('path')
const PORT = process.env.PORT || 5000

express()
  .use(express.static(path.join(__dirname, 'public')))
  .set('views', path.join(__dirname, 'views'))
  .set('view engine', 'ejs')
  .get('/', (req, res) => res.render('pages/index2'))
	.get('/bc.jpg', function (req, res) {
		res.sendFile(__dirname + '/bc.jpg');          
	})
  .listen(PORT, () => console.log(`Listening on ${ PORT }`))
*/
const PORT = process.env.PORT || 5000
var express = require('express');
var path = require('path');
var app = express();
  app.use(express.static(path.join(__dirname, 'public')))
  app.set('views', path.join(__dirname, 'views'))
  app.set('view engine', 'ejs')
  app.get('/', (req, res) => res.render('pages/index2'))
	app.get('/bc.jpg', function (req, res) {
		res.sendFile(__dirname + '/bc.jpg');          
	})
  //app.listen(PORT, () => console.log(`Listening on ${ PORT }`))
  