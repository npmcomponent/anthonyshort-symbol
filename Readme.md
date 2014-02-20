*This repository is a mirror of the [component](http://component.io) module [anthonyshort/symbol](http://github.com/anthonyshort/symbol). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/anthonyshort-symbol`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# symbol

  Polyfill for ES6 symbols for ES5 browsers. Originally written by [Andrea Giammarchi](http://webreflection.blogspot.com.au/2013/03/simulating-es6-symbols-in-es5.html). I just made it into a Component so I can use it easily.

## Installation

    $ component install anthonyshort/symbol

## API

    var Symbol = require('symbol');
    var data = {};
    var hidden = new Symbol();
    data[hidden] = "Secret files";
    console.log(data); // {}
    console.log(data[hidden]); // "Secret files";

## License

  MIT
