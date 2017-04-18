# npmdoc-eventsource

#### api documentation for  [eventsource (v1.0.0)](http://github.com/EventSource/eventsource)  [![npm package](https://img.shields.io/npm/v/npmdoc-eventsource.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eventsource) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eventsource.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eventsource)

#### W3C compliant EventSource client for Node.js and browser (polyfill)

[![NPM](https://nodei.co/npm/eventsource.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eventsource)

- [https://npmdoc.github.io/node-npmdoc-eventsource/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eventsource/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventsource/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventsource/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eventsource/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eventsource/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aslak Hellesøy"
    },
    "bugs": {
        "url": "http://github.com/EventSource/eventsource/issues"
    },
    "dependencies": {
        "original": "^1.0.0"
    },
    "description": "W3C compliant EventSource client for Node.js and browser (polyfill)",
    "devDependencies": {
        "express": "^4.13.4",
        "mocha": "^3.2.0",
        "nyc": "^10.2.0",
        "serve-static": "^1.10.2",
        "sse": "^0.0.6",
        "standard": "^10.0.2",
        "webpack": "^2.4.1"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "27f11c7a3ea5e129870de1b3ad05d09da60e2a20",
        "tarball": "https://registry.npmjs.org/eventsource/-/eventsource-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "gitHead": "3a4445f431560ef67c9cdbe74c238c94a5aecf3b",
    "homepage": "http://github.com/EventSource/eventsource",
    "keywords": [
        "eventsource",
        "http",
        "streaming",
        "sse",
        "polyfill"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/EventSource/eventsource/raw/master/LICENSE"
        }
    ],
    "main": "./lib/eventsource",
    "maintainers": [
        {
            "name": "aslakhellesoy"
        },
        {
            "name": "rexxars"
        }
    ],
    "name": "eventsource",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/EventSource/eventsource.git"
    },
    "scripts": {
        "coverage": "nyc --reporter=html --reporter=text _mocha --reporter spec",
        "polyfill": "webpack lib/eventsource-polyfill.js example/eventsource-polyfill.js",
        "postpublish": "git push && git push --tags",
        "test": "mocha --reporter spec && standard"
    },
    "standard": {
        "ignore": [
            "example/eventsource-polyfill.js"
        ]
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
