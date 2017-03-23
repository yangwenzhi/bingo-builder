# bingo-builder

### install 
通过npm安装 
$ npm install bingo-builder --save


### Usage
<pre>
var builder = require('bingo-builder');
var bingo = new builder({compress : 0});

bingo.build('file.js', function(err, res){
    console.log(err, res)
});
</pre>

#### file.js
<pre>
//##include('../jquery.js');
//##include('../a.js');
$(document).ready(function () {
  alert('1')
});
</pre>
