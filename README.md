# api documentation for  [node-lifx (v0.8.0)](https://github.com/MariusRumpf/node-lifx#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-lifx.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-lifx) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-lifx.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-lifx)
#### Node.js implementation of the LIFX protocol

[![NPM](https://nodei.co/npm/node-lifx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-lifx)

- [https://npmdoc.github.io/node-npmdoc-node-lifx/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-lifx/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-lifx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-lifx/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-lifx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-lifx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marius Rumpf"
    },
    "bugs": {
        "url": "https://github.com/MariusRumpf/node-lifx/issues"
    },
    "dependencies": {
        "eventemitter3": "^2.0.2",
        "lodash": "^4.5.0"
    },
    "description": "Node.js implementation of the LIFX protocol",
    "devDependencies": {
        "babel-core": "^6.0.15",
        "babel-preset-es2015": "^6.0.15",
        "chai": "^3.0.0",
        "codecov.io": "^0.1.6",
        "eslint": "^2.13.1",
        "istanbul": "^0.4.0",
        "lolex": "^1.4.0",
        "mocha": "^2.2.4"
    },
    "directories": {
        "test": "test",
        "lib": "lib",
        "example": "example"
    },
    "dist": {
        "shasum": "2f96993562100b9155e2ec49ddecbfc33c9a3dae",
        "tarball": "https://registry.npmjs.org/node-lifx/-/node-lifx-0.8.0.tgz"
    },
    "gitHead": "29a1263cc6afda9c354da02d36422109f0b32db9",
    "homepage": "https://github.com/MariusRumpf/node-lifx#readme",
    "keywords": [
        "bulb",
        "lifx",
        "light",
        "lightbulb"
    ],
    "license": "MIT",
    "main": "./lib/lifx",
    "maintainers": [
        {
            "name": "mariusrumpf"
        }
    ],
    "name": "node-lifx",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MariusRumpf/node-lifx.git"
    },
    "scripts": {
        "lint": "eslint lib/ test/ example/ cli.js",
        "pretest": "npm run lint",
        "report-coverage": "cat ./coverage/coverage.json | node_modules/codecov.io/bin/codecov.io.js",
        "test": "istanbul cover -root lib/ node_modules/mocha/bin/_mocha -- -u tdd -r babelhook --recursive test/unit/"
    },
    "version": "0.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
