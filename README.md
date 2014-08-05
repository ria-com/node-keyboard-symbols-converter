## node-keyboard-symbols-converter ##
Simple helper that convert keyboard symbols from Russian or Ukrainian to English.
## Installing ##
Add to you package.json file:

    "dependencies": {
       "converter": "git://github.com/ria-com/node-keyboard-symbols-converter.git"
    }
Then run `npm install`
## Usage example ##

    var converter = require('node-keyboard-symbols-converter');
    console.log(converter.convert('привет', 'ru-UA', 'en-US')); // --> ghbdtn

