Hey guys, how are you? I don´t know where to warn about a little "mistake" at 8.x version. Please take a look and forgive me if that´s not the right spot  for that.
At 7.x version i could use code like that on webpack.mix.js:

const mix = require('laravel-mix');

mix.
 .sass('resources/scss/geral/diversos.scss', '../resources/css/diversos.css')
 
 with "../resources..." for after that i so could use 
 
 .styles([
        'node_modules/bootstrap/dist/css/bootstrap.min.css',
        'node_modules/font-awesome/css/font-awesome.min.css'
  ]);
  
  for put it on public folder together at one.
  
  But now it isn´t an option anymore.
  Thanks!!!
