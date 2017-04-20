# npmtest-hyperdrive

#### basic test coverage for  [hyperdrive (v8.3.0)](https://github.com/mafintosh/hyperdrive)  [![npm package](https://img.shields.io/npm/v/npmtest-hyperdrive.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hyperdrive) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hyperdrive.svg)](https://travis-ci.org/npmtest/node-npmtest-hyperdrive)

#### Hyperdrive is a secure, real time distributed file system

[![NPM](https://nodei.co/npm/hyperdrive.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hyperdrive)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hyperdrive/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperdrive/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hyperdrive/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hyperdrive/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hyperdrive/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hyperdrive/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hyperdrive/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hyperdrive/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hyperdrive/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperdrive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hyperdrive/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hyperdrive/build/test-report.html](https://npmtest.github.io/node-npmtest-hyperdrive/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hyperdrive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hyperdrive/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hyperdrive/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hyperdrive/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hyperdrive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hyperdrive/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hyperdrive/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hyperdrive/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Buus",
        "url": "@mafintosh"
    },
    "bugs": {
        "url": "https://github.com/mafintosh/hyperdrive/issues"
    },
    "dependencies": {
        "append-tree": "^2.0.5",
        "duplexify": "^3.5.0",
        "from2": "^2.3.0",
        "hypercore": "^5.5.0",
        "inherits": "^2.0.3",
        "mutexify": "^1.1.0",
        "protocol-buffers": "^3.2.1",
        "random-access-file": "^1.5.0",
        "sodium-native": "^1.8.0",
        "stream-collector": "^1.0.1",
        "thunky": "^1.0.2"
    },
    "description": "Hyperdrive is a secure, real time distributed file system",
    "devDependencies": {
        "random-access-memory": "^2.3.0",
        "sodium-signatures": "^2.0.0",
        "standard": "^9.0.2",
        "tape": "^4.6.3",
        "temporary-directory": "^1.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "88c0a82c1a58fc82e3a1fd4e78006f44079ad731",
        "tarball": "https://registry.npmjs.org/hyperdrive/-/hyperdrive-8.3.0.tgz"
    },
    "gitHead": "d8de07846b3292205d94ca790a18fc1aabe6a95e",
    "homepage": "https://github.com/mafintosh/hyperdrive",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mafintosh"
        }
    ],
    "name": "hyperdrive",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mafintosh/hyperdrive.git"
    },
    "scripts": {
        "test": "standard && tape test/*.js"
    },
    "version": "8.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
