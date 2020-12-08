# Mocha tests

## Installation

Go to the root directory (where the `package.json` is located) and run:

```bash
npm install
```

## Running tests

Run the tests once:

```bash
npm test
```

Run the test and re-run them once a file changes:

```bash
npm run tdd
```

Run the test with code coverage:

```bash
npm run coverage
```

### What's included

* Mocha to run tests
* [Sinon JS](http://sinonjs.org/) for all stub, spy and mocking needs
* [Assertions using Chai]((http://chaijs.com/api/bdd)), extended with the
  [`sinon-chai` plugin](https://github.com/domenic/sinon-chai).
  * The Expect style is used by default,
  you can change to use `Should` instead, in `test/common.js`,