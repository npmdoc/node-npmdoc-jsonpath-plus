# npmdoc-jsonpath-plus

#### api documentation for  [jsonpath-plus (v0.16.0)](https://github.com/s3u/JSONPath)  [![npm package](https://img.shields.io/npm/v/npmdoc-jsonpath-plus.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jsonpath-plus) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jsonpath-plus.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jsonpath-plus)

#### A JS implementation of JSONPath with some additional operators

[![NPM](https://nodei.co/npm/jsonpath-plus.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsonpath-plus)

- [https://npmdoc.github.io/node-npmdoc-jsonpath-plus/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsonpath-plus/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsonpath-plus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsonpath-plus/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jsonpath-plus/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jsonpath-plus/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stefan Goessner"
    },
    "bugs": {
        "url": "https://github.com/s3u/JSONPath/issues/"
    },
    "contributors": [
        {
            "name": "Prof. Gössner"
        },
        {
            "name": "Subbu Allamaraju"
        },
        {
            "name": "Mike Brevoort"
        },
        {
            "name": "Robert Krahn"
        },
        {
            "name": "Brett Zamir"
        },
        {
            "name": "Richard Schneider"
        }
    ],
    "dependencies": {},
    "description": "A JS implementation of JSONPath with some additional operators",
    "devDependencies": {
        "eslint": "^1.10.3",
        "eslint-config-standard": "^4.4.0",
        "eslint-plugin-standard": "^1.3.1",
        "nodeunit": "0.9.0",
        "remark": "^4.1.2",
        "remark-lint": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fe441b23f03ec6979a5603513988cd3edb7db5dc",
        "tarball": "https://registry.npmjs.org/jsonpath-plus/-/jsonpath-plus-0.16.0.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "b5153360df121723896ca1277815101059afa65a",
    "homepage": "https://github.com/s3u/JSONPath",
    "keywords": [
        "json",
        "jsonpath"
    ],
    "license": "MIT",
    "main": "./lib/jsonpath",
    "maintainers": [
        {
            "name": "brettz9"
        }
    ],
    "name": "jsonpath-plus",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/s3u/JSONPath.git"
    },
    "scripts": {
        "browser-test": "npm run lint && node ./test-helpers/nodeunit-server",
        "eslint": "eslint test lib test-helpers",
        "lint": "npm run eslint && npm run remark",
        "nodeunit": "nodeunit test",
        "remark": "remark -q -f .",
        "start": "npm run browser-test",
        "test": "npm run lint && npm run nodeunit"
    },
    "version": "0.16.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
