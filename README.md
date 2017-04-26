# npmtest-bcrypt

#### basic test coverage for  [bcrypt (v1.0.2)](https://github.com/kelektiv/node.bcrypt.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bcrypt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bcrypt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bcrypt.svg)](https://travis-ci.org/npmtest/node-npmtest-bcrypt)

#### A bcrypt library for NodeJS.

[![NPM](https://nodei.co/npm/bcrypt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bcrypt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bcrypt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bcrypt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bcrypt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bcrypt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bcrypt/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-bcrypt/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-bcrypt/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bcrypt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bcrypt/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bcrypt/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bcrypt/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bcrypt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bcrypt/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bcrypt/build/test-report.html](https://npmtest.github.io/node-npmtest-bcrypt/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bcrypt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bcrypt/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bcrypt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bcrypt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bcrypt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bcrypt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bcrypt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bcrypt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Campbell",
        "url": "https://github.com/ncb000gt"
    },
    "binary": {
        "module_name": "bcrypt_lib",
        "module_path": "./lib/binding/",
        "host": "https://github.com",
        "remote_path": "/kelektiv/node.bcrypt.js/releases/download/v{version}/"
    },
    "bugs": {
        "url": "https://github.com/kelektiv/node.bcrypt.js/issues"
    },
    "contributors": [
        {
            "name": "Antonio Salazar Cardozo",
            "url": "https://github.com/Shadowfiend"
        },
        {
            "name": "Van Nguyen",
            "url": "https://github.com/thegoleffect"
        },
        {
            "name": "David Trejo",
            "url": "https://github.com/dtrejo"
        },
        {
            "name": "Ben Glow",
            "url": "https://github.com/pixelglow"
        },
        {
            "name": "NewITFarmer.com",
            "url": "https://github.com/newitfarmer"
        },
        {
            "name": "Alfred Westerveld",
            "url": "https://github.com/alfredwesterveld"
        },
        {
            "name": "Vincent Côté-Roy",
            "url": "https://github.com/vincentcr"
        },
        {
            "name": "Lloyd Hilaiel",
            "url": "https://github.com/lloyd"
        },
        {
            "name": "Roman Shtylman",
            "url": "https://github.com/shtylman"
        },
        {
            "name": "Vadim Graboys",
            "url": "https://github.com/vadimg"
        },
        {
            "name": "Ben Noorduis",
            "url": "https://github.com/bnoordhuis"
        },
        {
            "name": "Nate Rajlich",
            "url": "https://github.com/tootallnate"
        },
        {
            "name": "Sean McArthur",
            "url": "https://github.com/seanmonstar"
        },
        {
            "name": "Fanie Oosthuysen",
            "url": "https://github.com/weareu"
        },
        {
            "name": "Amitosh Swain Mahapatra",
            "url": "https://github.com/Agathver"
        }
    ],
    "dependencies": {
        "bindings": "1.2.1",
        "nan": "2.5.0",
        "node-pre-gyp": "0.6.32"
    },
    "description": "A bcrypt library for NodeJS.",
    "devDependencies": {
        "nodeunit": "~0.9.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d05fc5d223173e0e28ec381c0f00cc25ffaf2736",
        "tarball": "https://registry.npmjs.org/bcrypt/-/bcrypt-1.0.2.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "gitHead": "9036615a24c51f0d125ae39efbf9b943f16c8571",
    "homepage": "https://github.com/kelektiv/node.bcrypt.js#readme",
    "keywords": [
        "bcrypt",
        "password",
        "auth",
        "authentication",
        "encryption",
        "crypt",
        "crypto"
    ],
    "license": "MIT",
    "main": "./bcrypt",
    "maintainers": [
        {
            "name": "ncb000gt"
        },
        {
            "name": "tootallnate"
        },
        {
            "name": "jfirebaugh"
        },
        {
            "name": "defunctzombie"
        }
    ],
    "name": "bcrypt",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kelektiv/node.bcrypt.js.git"
    },
    "scripts": {
        "install": "node-pre-gyp install --fallback-to-build",
        "test": "npm install --build-from-source && nodeunit test"
    },
    "version": "1.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
