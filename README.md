# npm-boilerplate

[![Build Status](https://travis-ci.org/apiaryio/npm-boilerplate.png)](https://travis-ci.org/apiaryio/npm-boilerplate)
[![Dependency Status](https://david-dm.org/apiaryio/npm-boilerplate.png)](https://david-dm.org/apiaryio/npm-boilerplate)
[![devDependency Status](https://david-dm.org/apiaryio/npm-boilerplate/dev-status.png)](https://david-dm.org/apiaryio/npm-boilerplate#info=devDependencies)


## Scripts

- `scripts/bdd` - watch on file changes and run Mocha tests if some file changes 
- `scripts/build` - remove `/lib` directory and render `.coffee` files from `/src`
- `scripts/prepublish` - run test and if passed then build
- `scripts/test` - run tests

## Do not forget to edit package json

- package `name`
- pacakge `description`
- path to your `main` file
- `version`
- `author`
- `keywords`
- `repository`
- `homepage`
- do not forget to add possible executables to `bin` section

## Add example usage 
```javascript
var boilerplate = require('npm-boilerplate');

boilerplate = boilerplate.boil(something);

console.log(boilerplate);
```

See more additional description

## Add API Reference

`boil(something)` - boils a plate

- - - 

NOTE: Add some possible note

