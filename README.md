# rgb-hex-converter

> Convert color values between RGB <-> HEX

## Install

```
$ npm install --save rgb-hex-converter
```

## Usage

```js
const converter = require('rgb-hex-converter');

converter.RGBtoHEX(255, 0, 0);
//=> 'ff0000'

converter.RGBtoHEX({
    r: 255,
    g: 0,
    b: 0
});
//=> 'ff0000'

converter.HEXtoRGB('ff0000');
/*
=> {
    r: 255,
    g: 0,
    b: 0
}
*/
```

## License

MIT © [Arka Roy](https://www.arkaroy.net)