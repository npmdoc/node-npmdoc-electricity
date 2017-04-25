# npmdoc-electricity

#### basic api documentation for  [electricity (v1.7.0)](https://github.com/mediocre/electricity#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-electricity.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electricity) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electricity.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electricity)

#### An alternative to the built-in Express middleware for serving static files. Electricity follows a number of best practices for making web pages fast.

[![NPM](https://nodei.co/npm/electricity.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electricity)

- [https://npmdoc.github.io/node-npmdoc-electricity/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electricity/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electricity/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electricity/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electricity/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electricity/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/mediocre/electricity/issues"
    },
    "dependencies": {
        "mime": "1.3.x",
        "negotiator": "0.6.x",
        "node-sass": "3.11.x",
        "react-tools": "0.13.x",
        "sass-graph": "2.1.x",
        "snockets": "1.3.x",
        "uglify-js": "2.7.x",
        "uglifycss": "0.0.x",
        "watch": "1.0.x"
    },
    "description": "An alternative to the built-in Express middleware for serving static files. Electricity follows a number of best practices for making web pages fast.",
    "devDependencies": {
        "buffer-compare": "*",
        "ejs": "*",
        "express": "*",
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "4260276fa2bd1aed9594cc390176b1950970b335",
        "tarball": "https://registry.npmjs.org/electricity/-/electricity-1.7.0.tgz"
    },
    "gitHead": "3c9ded8900085b0ef76e27987b5cf36a63ad145b",
    "homepage": "https://github.com/mediocre/electricity#readme",
    "keywords": [
        "asset",
        "css",
        "express",
        "react",
        "sass",
        "static",
        "snockets"
    ],
    "main": "./lib",
    "maintainers": [
        {
            "name": "freshlogic"
        },
        {
            "name": "harrisonm"
        },
        {
            "name": "mediocre"
        }
    ],
    "name": "electricity",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mediocre/electricity.git"
    },
    "scripts": {
        "app": "node test/app.js",
        "quicktest": "mocha --reporter spec -g watcher -i",
        "test": "mocha --reporter spec -t 21000",
        "watch": "mocha --reporter spec -w -g watcher -i"
    },
    "version": "1.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
