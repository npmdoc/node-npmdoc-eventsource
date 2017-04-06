# api documentation for  [eventsource (v0.2.2)](http://github.com/aslakhellesoy/eventsource)  [![npm package](https://img.shields.io/npm/v/npmdoc-eventsource.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eventsource) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eventsource.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eventsource)
#### W3C compliant EventSource client for Node.js and browser (polyfill)

[![NPM](https://nodei.co/npm/eventsource.png?downloads=true)](https://www.npmjs.com/package/eventsource)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventsource/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-eventsource_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventsource/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eventsource/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eventsource/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aslak Hellesøy",
        "email": "aslak.hellesoy@gmail.com"
    },
    "bugs": {
        "url": "http://github.com/aslakhellesoy/eventsource/issues"
    },
    "dependencies": {
        "original": "^1.0.0"
    },
    "description": "W3C compliant EventSource client for Node.js and browser (polyfill)",
    "devDependencies": {
        "express": "^4.13.4",
        "mocha": "^2.4.5",
        "serve-static": "^1.10.2",
        "sse": "^0.0.6",
        "webpack": "^1.12.14"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "8ac0576cbd16ee83478b3faaf27bdc7b7c8fcca9",
        "tarball": "https://registry.npmjs.org/eventsource/-/eventsource-0.2.2.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "b59da74de5916c45489f6362724f5225bae89e9a",
    "homepage": "http://github.com/aslakhellesoy/eventsource",
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
            "url": "http://github.com/aslakhellesoy/eventsource/raw/master/LICENSE"
        }
    ],
    "main": "./lib/eventsource",
    "maintainers": [
        {
            "name": "aslakhellesoy",
            "email": "aslak.hellesoy@gmail.com"
        },
        {
            "name": "rexxars",
            "email": "rexxars@gmail.com"
        }
    ],
    "name": "eventsource",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/aslakhellesoy/eventsource.git"
    },
    "scripts": {
        "polyfill": "webpack lib/eventsource-polyfill.js example/eventsource-polyfill.js",
        "postpublish": "git push && git push --tags",
        "test": "mocha --reporter spec"
    },
    "version": "0.2.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eventsource](#apidoc.module.eventsource)
1.  [function <span class="apidocSignatureSpan">eventsource.</span>super_ ()](#apidoc.element.eventsource.super_)
1.  number <span class="apidocSignatureSpan">eventsource.</span>CLOSED
1.  number <span class="apidocSignatureSpan">eventsource.</span>CONNECTING
1.  number <span class="apidocSignatureSpan">eventsource.</span>OPEN



# <a name="apidoc.module.eventsource"></a>[module eventsource](#apidoc.module.eventsource)

#### <a name="apidoc.element.eventsource.super_"></a>[function <span class="apidocSignatureSpan">eventsource.</span>super_ ()](#apidoc.element.eventsource.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
