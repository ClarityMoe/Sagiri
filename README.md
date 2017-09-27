# Sagiri
A simple, lightweight and actually good JS wrapper for the SauceNAO API.

## Installation

```js
npm install @sr229/sagiri
```

## Usage

Example:
```js
const Sagiri = require('sagiri');
const handler = new Sagiri('TOKEN'); // or new Sagiri('TOKEN', number of results)

handler.getSauce('http://i.imgur.com/5yFTeRV.png').then(res => {
    console.log(res);
});
```

## API 

Documentation for the module is available [here](./API.md).

## Contributing

All contributions are accepted! If you think you can bring uploading support, or make the lib perform better, make a PR and start coding!

## Copyright

Copyright 2017 (c) ClarityMoe. This Library is from the [Clara base project](https://github.com/ClaraIO/Clara).

Sagiri is a character from Eromanga-sensei. All rights reserved to her authors.