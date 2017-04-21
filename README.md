# npmdoc-mongoose-id-validator

#### api documentation for  [mongoose-id-validator (v0.4.2)](https://github.com/CampbellSoftwareSolutions/mongoose-id-validator)  [![npm package](https://img.shields.io/npm/v/npmdoc-mongoose-id-validator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mongoose-id-validator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mongoose-id-validator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mongoose-id-validator)

#### Mongoose plugin to validate that ObjectID references refer to objects that actually exist in the referenced collection

[![NPM](https://nodei.co/npm/mongoose-id-validator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongoose-id-validator)

- [https://npmdoc.github.io/node-npmdoc-mongoose-id-validator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongoose-id-validator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongoose-id-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongoose-id-validator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mongoose-id-validator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mongoose-id-validator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mongoose-id-validator",
    "version": "0.4.2",
    "description": "Mongoose plugin to validate that ObjectID references refer to objects that actually exist in the referenced collection",
    "author": {
        "name": "Martin Campbell",
        "url": "http://www.campbellsoftware.co.uk"
    },
    "keywords": [
        "mongoose",
        "objectid",
        "id",
        "validate",
        "validator",
        "exists",
        "mongodb"
    ],
    "homepage": "https://github.com/CampbellSoftwareSolutions/mongoose-id-validator",
    "repository": {
        "type": "git",
        "url": "git://github.com/CampbellSoftwareSolutions/mongoose-id-validator"
    },
    "license": "LGPL-3.0+",
    "readmeFilename": "README.md",
    "bugs": {
        "url": "https://github.com/CampbellSoftwareSolutions/mongoose-id-validator/issues"
    },
    "engine": "node >= 0.4.0",
    "main": "index.js",
    "scripts": {
        "test": "./node_modules/.bin/mocha -R spec"
    },
    "devDependencies": {
        "mongoose": "*",
        "async": "~0.2.9",
        "should": "~3.0.1",
        "mocha": "^2.2.1"
    },
    "dependencies": {
        "clone": "^1.0.2",
        "traverse": "^0.6.6"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
