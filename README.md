# jstransformer-j140 [![The MIT License][license-img]][license-url]

[j140](https://github.com/tunnckoCore/j140) support for [JSTransformers][jstransformers-url]

[![travis build status][travis-img]][travis-url] [![coverage status][coveralls-img]][coveralls-url] [![dependency status][david-img]][david-url] [![npmjs.com][npmjs-img]][npmjs-url]


## Install
```
npm install jstransformer-j140 --save
```


## Usage
> For more use-cases see the **tests** in [test folder](./test) or see the [JSTransformer API](http://github.com/jstransformers/jstransformer#api) for more details.

```js
var es6template = require('jstransformer')(require('jstransformer-j140'));

var locals = {
  place: 'world',
  user: {
    name: 'Charlike'
  }
};

es6template.render('Hello #{place} and #{user.name}!', locals).body
//=> 'Hello world and Charlike!'
```


## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/tunnckoCore/jstransformer-j140/issues/new).


## License
[The MIT License][license-url]


[npmjs-url]: https://www.npmjs.com/package/jstransformer-j140
[npmjs-img]: https://img.shields.io/npm/v/jstransformer-j140.svg

[license-url]: ./LICENSE
[license-img]: https://img.shields.io/badge/license-MIT-blue.svg

[travis-url]: https://travis-ci.org/tunnckoCore/jstransformer-j140
[travis-img]: https://img.shields.io/travis/tunnckoCore/jstransformer-j140.svg

[coveralls-url]: https://coveralls.io/r/tunnckoCore/jstransformer-j140
[coveralls-img]: https://img.shields.io/coveralls/tunnckoCore/jstransformer-j140.svg

[david-url]: https://david-dm.org/tunnckoCore/jstransformer-j140
[david-img]: https://img.shields.io/david/tunnckoCore/jstransformer-j140.svg

[jstransformers-url]: http://github.com/jstransformers
