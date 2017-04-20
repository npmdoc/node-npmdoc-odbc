# npmdoc-odbc

#### api documentation for  [odbc (v1.2.1)](http://github.com/wankdanker/node-odbc/)  [![npm package](https://img.shields.io/npm/v/npmdoc-odbc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-odbc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-odbc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-odbc)

#### unixodbc bindings for node

[![NPM](https://nodei.co/npm/odbc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/odbc)

- [https://npmdoc.github.io/node-npmdoc-odbc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-odbc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-odbc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-odbc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-odbc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-odbc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "odbc",
    "description": "unixodbc bindings for node",
    "version": "1.2.1",
    "main": "lib/odbc.js",
    "homepage": "http://github.com/wankdanker/node-odbc/",
    "repository": {
        "type": "git",
        "url": "git://github.com/wankdanker/node-odbc.git"
    },
    "bugs": {
        "url": "https://github.com/w1nk/node-odbc/issues"
    },
    "contributors": [
        {
            "name": "Dan VerWeire"
        },
        {
            "name": "Lee Smith"
        }
    ],
    "directories": {
        "lib": "."
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "scripts": {
        "install": "node-gyp configure build",
        "test": "cd test && node run-tests.js"
    },
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.0.9"
    },
    "gypfile": true
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
