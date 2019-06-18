# secp256r1-js
[![CircleCI](https://circleci.com/gh/trustedkey/secp256r1-js.svg?style=svg)](https://circleci.com/gh/trustedkey/secp256r1-js)

Pure JS implementation of secp256r1 signing, verification, recovery ECDSA.

The code works as-is both in browsers and NodeJS, without the need of a bundler.

## Usage
```sh
npm install @trustedkey/secp256r1-js
```
or
```html
<script src="https://unpkg.com/bn.js@4.11.8/lib/bn.js" type="text/javascript"></script>
<script src="https://unpkg.com/@trustedkey/secp256r1-js@1.0.0/src/secp256r1.js" type="text/javascript"></script>
```

## Development
```sh
npm install
npm test
```

Open `test/test.html` to run the same tests in the browser.

# The MIT License
Copyright 2018 Enuma Technologies Limited.
Copyright 2019 Trusted Key Solutions Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
