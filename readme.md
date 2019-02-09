# wiredep-away [![Build Status](https://travis-ci.org/azachar/wiredep-away.svg?branch=master)](https://travis-ci.org/azachar/wiredep-away)
> Wire your yarn `@bower-dependencies\***` to your source code with after you ditched [bower](http://bower.io) with [bower-away](https://github.com/sheerun/bower-away).

## Getting Started
Install the module with [npm](https://npmjs.org):

```bash
$ npm install --save azachar/wiredep-away#master
```

Convert your dependencies (if you haven't already):

```bash
$ npm -g install bower-away
```

```bash
$ bower-away
```

Replace your `require('wiredep')` with `require('wiredep-away')` and you are good to go.

## NOTE
This module is currently under development.
The idea is to have all tests passing on the original source code, then add new tests and then implement the bower-away approach.

Also, tests should pass on all NodeJS LTS environments.

There were some forks of original `wiredep` that did some patches with `bower-away` approach, but I was not happy with it since it was done without any tests and moreover was not working on LTS environments...

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using `npm run style` or `npm test`.

Please note to install test's symbolic links correctly on your OS run `npm run setup`.


## License
Copyright (c) 2019 Andrej Zachar. Initially forked from Stephen Sawchuk. Licensed under the MIT license.
