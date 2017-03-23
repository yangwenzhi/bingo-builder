# bingo-builder
$ npm install bingo-builder --save

var builder = require('bingo-builder');
var bingo = new builder({compress : 0});

bingo.build('file.js', function(err, res){
    console.log(err, res)
});

file.js
//##include('../jquery.js');
//##include('../a.js');
$(document).ready(function () {
  alert('1')
});
