# Stream to upper

Convert streams to upper case.

## Example

```javascript
var toUpper = require('toupper');

process.stdin.pipe(toUpper()).pipe(process.stdout);
```

```sh
$ node main.js
test
TEST
asdf
ASDF
```

## Install

```sh
$ npm install toupper
```

## License

[MIT](http://rumpl.mit-license.org)
