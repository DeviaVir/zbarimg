# zbarimg

Scan photos using `zbarimg` in node.js. This module is a wrapper around the `zbarimg` command from [ZBar bar code reader](http://zbar.sourceforge.net).

## Installation

	npm install zbarimg
	
## Requirements

[ZBar bar code reader](http://zbar.sourceforge.net) must be installed on your system. Make sure the command `zbarimg` is working.
	
## Usage

```js
var zbarimg = require('zbarimg')

zbarimg('photo.png', function(err, code) {

	console.log(code)
})
```

