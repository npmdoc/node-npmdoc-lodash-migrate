# npmdoc-lodash-migrate

#### basic api documentation for  [lodash-migrate (v0.3.16)](https://github.com/lodash/lodash-migrate#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-lodash-migrate.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lodash-migrate) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lodash-migrate.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lodash-migrate)

#### Migrate to the latest Lodash release.

[![NPM](https://nodei.co/npm/lodash-migrate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lodash-migrate)

- [https://npmdoc.github.io/node-npmdoc-lodash-migrate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lodash-migrate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lodash-migrate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lodash-migrate/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lodash-migrate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lodash-migrate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John-David Dalton",
        "url": "http://allyoucanleet.com/"
    },
    "bugs": {
        "url": "https://github.com/lodash/lodash-migrate/issues"
    },
    "contributors": [
        {
            "name": "John-David Dalton",
            "url": "http://allyoucanleet.com/"
        },
        {
            "name": "Mathias Bynens",
            "url": "https://mathiasbynens.be/"
        }
    ],
    "dependencies": {},
    "description": "Migrate to the latest Lodash release.",
    "devDependencies": {
        "lodash": "^3.10.1",
        "qunit-extras": "^3.0.0",
        "qunitjs": "^2.1.0",
        "webpack": "^1.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ecc396276082e915091dded8d554aa1ddc08088d",
        "tarball": "https://registry.npmjs.org/lodash-migrate/-/lodash-migrate-0.3.16.tgz"
    },
    "files": [
        "dist",
        "lib",
        "index.js",
        "lodash.js"
    ],
    "greenkeeper": {
        "ignore": [
            "lodash"
        ]
    },
    "homepage": "https://github.com/lodash/lodash-migrate#readme",
    "keywords": [
        "compatibility",
        "lodash",
        "update"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jdalton"
        },
        {
            "name": "mathias"
        }
    ],
    "name": "lodash-migrate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lodash/lodash-migrate.git"
    },
    "scripts": {
        "build": "npm run build:dev & npm run build:prod",
        "build:dev": "webpack index.js dist/lodash-migrate.js --env development",
        "build:prod": "webpack index.js dist/lodash-migrate.min.js --env production",
        "prepublish": "npm run build",
        "test": "node test"
    },
    "version": "0.3.16",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
