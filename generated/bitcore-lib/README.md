Bitcore Library
=======

[![NPM Package](https://img.shields.io/npm/v/bitcore-lib.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-lib)
[![Build Status](https://img.shields.io/travis/bitpay/bitcore-lib.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore-lib)
[![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore-lib.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore-lib)

A pure and powerful JavaScript Blackcoin library.

## Principles

Blackcoin is a powerful new peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Blackcoin network allows for highly resilient blackcoin infrastructure, and the developer community needs reliable, open-source tools to implement blackcoin apps and services.


## Security

We're using Blackcore in production, as are [many others](http://blackcoin.io), but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.

If you find a security issue, please email security@bitpay.com.

## Building the Browser Bundle

To build a bitcore-lib full bundle for the browser:

```sh
gulp browser
```

This will generate files named `bitcore-lib.js` and `bitcore-lib.min.js`.

You can also use our pre-generated files, provided for each release along with a PGP signature by one of the project's maintainers. To get them, checkout a release commit (for example, https://github.com/bitpay/bitcore-lib/commit/e33b6e3ba6a1e5830a079e02d949fce69ea33546 for v0.12.6).


## Development & Tests

```sh
git clone -b blackcore-lib https://github.com/janko33/bitcore-lib
cd bitcore-lib
npm install
```

## License

Code released under [the MIT license](https://github.com/bitpay/bitcore-lib/blob/master/LICENSE).

Copyright 2013-2015 BitPay, Inc. Bitcore is a trademark maintained by BitPay, Inc.
Copyright 2016 Obsidiancvt.
