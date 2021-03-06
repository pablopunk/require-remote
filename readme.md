
# import-url

<p align="center">
  <i>Require modules from any URL</i>
</p>
<p align="center">
  <a href="https://www.npmjs.com/package/import-url"><img src="https://img.shields.io/npm/dt/import-url.svg" /></a>
</p>


## Install

```bash
npm install import-url
```

## Usage

```js
const foo = await require('import-url')('module.now.sh')
console.log(foo()) //=> 'awesome!'
```

Right now it doesn't support modules requiring other modules. So if your remote module does a `require()` it will fail.

## Contribute

Feel free to open an _issue_ or a _PR_.


## License

[__MIT license__](license)

## Related

This module used to be named `require-remote` and still still available [on npm](https://www.npmjs.com/package/require-remote).

## Author

| ![me](https://www.gravatar.com/avatar/fa50aeff0ddd6e63273a068b04353d9d?s=100) |
| ----------------------------------------------------------------------------- |
| © 2017 [Pablo Varela](http://pablo.life)                                      |
