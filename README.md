# rgb-hex-converter

> Convert color values between RGB <-> HEX

## Install

```
$ npm install --save rgb-hex-converter
```

## Usage

```js
const converter = require('rgb-hex-converter');

// By arguments
converter.RGBtoHEX(255, 0, 0);
//=> 'ff0000'

// By object
converter.RGBtoHEX({
    r: 255,
    g: 0,
    b: 0
});
//=> 'ff0000'

// By array
converter.RGBtoHEX([255, 0, 0])
//=> 'ff0000'

// Hex value can be 3 or 6 characters with or without '#'.
// Valid arguments:
// ff0000
// f00
// #ff0000
// #f00
converter.HEXtoRGB('ff0000');
/*
=> {
    r: 255,
    g: 0,
    b: 0
}
*/

// Aliases
converter.rgb2hex(255, 0, 0);
converter.hex2rgb('ff0000');
```

## License

MIT © [Arka Roy](https://www.arkaroy.net)