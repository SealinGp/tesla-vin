# @sealingp/tesla-vin

![Last version](https://img.shields.io/github/tag/SealinGp/tesla-vin.svg?style=flat-square)
[![Coverage Status](https://img.shields.io/coveralls/SealinGp/tesla-vin.svg?style=flat-square)](https://coveralls.io/github/SealinGp/tesla-vin)
[![NPM Status](https://img.shields.io/npm/dm/@sealingp/tesla-vin.svg?style=flat-square)](https://www.npmjs.org/package/@sealingp/tesla-vin)

> Tesla Vehicle Identification Number (VIN) decoder fork with updates and maintenance. This is a maintained fork of the original [tesla-vin](https://github.com/teslahunt/tesla-vin) project.

## Install

```bash
$ npm install @sealingp/tesla-vin --save
```

## Usage

```js
const teslaVIN = require('@sealingp/tesla-vin')

const vinDecoded = teslaVIN('5YJ3F7EA2LF656311')

console.log(vinDecoded)
// {
//   bateryType: 'Nickel Manganese Cobalt (NMC)',
//   bodyType: 'Sedan 4 DR / RHD',
//   model: 'Tesla Model 3',
//   motor: 'Single Motor Standard (3DU 800A)',
//   photos: [
//     'https://cdn.jsdelivr.net/gh/SealinGp/tesla-vin@master/images/3/1.jpeg',
//     'https://cdn.jsdelivr.net/gh/SealinGp/tesla-vin@master/images/3/2.jpeg',
//     'https://cdn.jsdelivr.net/gh/SealinGp/tesla-vin@master/images/3/3.jpeg',
//     'https://cdn.jsdelivr.net/gh/SealinGp/tesla-vin@master/images/3/4.jpeg',
//     'https://cdn.jsdelivr.net/gh/SealinGp/tesla-vin@master/images/3/5.jpeg',
//   ],
//   plantOfManufacture: 'Tesla Fremont, California (USA)',
//   restraintSystems: 'Type 2 Manual seatbelts (FR, SR*3) with front Airbags, side Inflatable restraints',
//   sequenceNumber: 656311,
//   worldManufacturingIdentifier: 'Fremont, California',
//   year: 2020,
// }
```

## Why this fork?

This fork was created to maintain and update the original tesla-vin package which is no longer actively maintained. Updates include:
- Regular maintenance and bug fixes
- Support for newer Tesla models and VIN patterns
- Updated dependencies
- Improved documentation

## License

**@sealingp/tesla-vin** © [SealinGp](https://github.com/SealinGp), forked from [Tesla Hunt](https://teslahunt.io), released under the [MIT](https://github.com/SealinGp/tesla-vin/blob/master/LICENSE.md) License.<br>
Maintained by [SealinGp](https://github.com/SealinGp) with contributions from [Leo Zhang](https://github.com/SealinGp).

> GitHub [@SealinGp](https://github.com/SealinGp)
