
# wait

[![NPM version][npm-image]][npm-url]
[![Code style][standard-image]][standard-url]

wait block for use with running the motor forever

## Installation

    $ npm install ev3-js-wait

## Usage

```js
var wait = require('ev3-js-wait')
var TouchSensor = require('ev3-js-touch-sensor')

wait(function () {
  return TouchSensor(3).value === 1
})
```

## API

### wait(fn)

- `fn` - function that returns a conditional

## License

MIT

[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat
[standard-url]: https://github.com/feross/standard
[npm-image]: https://img.shields.io/npm/v/ev3-js-wait.svg?style=flat-square
[npm-url]: https://npmjs.org/package/ev3-js-wait
