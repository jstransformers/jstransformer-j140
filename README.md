# jstransformer-j140

[j140](https://github.com/tunnckoCore/j140) support for [JSTransformers](http://github.com/jstransformers).

[![Build Status](https://img.shields.io/travis/jstransformers/jstransformer-j140/master.svg)](https://travis-ci.org/jstransformers/jstransformer-j140)
[![Coverage Status](https://img.shields.io/codecov/c/github/jstransformers/jstransformer-j140/master.svg)](https://codecov.io/gh/jstransformers/jstransformer-j140)
[![Dependency Status](https://img.shields.io/david/jstransformers/jstransformer-j140/master.svg)](http://david-dm.org/jstransformers/jstransformer-j140)
[![NPM version](https://img.shields.io/npm/v/jstransformer-j140.svg)](https://www.npmjs.org/package/jstransformer-j140)

## Installation

    npm install jstransformer-j140

## API

```js
var engine = require('jstransformer')(require('jstransformer-j140'))

var locals = {
  place: 'world',
  user: {
    name: 'Charlike'
  }
}

engine.render('Hello #{place} and #{user.name}!', locals).body
//=> 'Hello world and Charlike!'
```

## License

MIT
