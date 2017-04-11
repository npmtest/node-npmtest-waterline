# test coverage for  [waterline (v0.11.11)](http://waterlinejs.org)  [![npm package](https://img.shields.io/npm/v/npmtest-waterline.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-waterline) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-waterline.svg)](https://travis-ci.org/npmtest/node-npmtest-waterline)
#### An ORM for Node.js and the Sails framework.

[![NPM](https://nodei.co/npm/waterline.png?downloads=true)](https://www.npmjs.com/package/waterline)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-waterline/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-waterline/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-waterline/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-waterline/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-waterline/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-waterline/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-waterline/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-waterline/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-waterline/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-waterline/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-waterline%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-waterline/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-waterline/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-waterline%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-waterline/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-waterline/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-waterline/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "http://sailsjs.com/bugs"
    },
    "contributors": [
        {
            "name": "particlebanana"
        },
        {
            "name": "mikermcneil"
        },
        {
            "name": "zolmeister"
        },
        {
            "name": "seerepo"
        }
    ],
    "dependencies": {
        "anchor": "~0.11.0",
        "async": "1.5.2",
        "bluebird": "3.2.1",
        "deep-diff": "0.3.3",
        "lodash": "3.10.1",
        "prompt": "0.2.14",
        "switchback": "2.0.0",
        "waterline-criteria": "~0.11.2",
        "waterline-schema": "~0.2.1"
    },
    "description": "An ORM for Node.js and the Sails framework.",
    "devDependencies": {
        "codeclimate-test-reporter": "0.3.1",
        "eslint": "1.10.3",
        "espree": "3.0.1",
        "istanbul": "0.4.2",
        "mocha": "2.4.5",
        "sails-memory": "github:balderdashy/sails-memory",
        "should": "8.2.1",
        "waterline-adapter-tests": "~0.11.2"
    },
    "directories": {},
    "dist": {
        "shasum": "6d2ec14d8f6caea49434adad8832ae4a1beeb288",
        "tarball": "https://registry.npmjs.org/waterline/-/waterline-0.11.11.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "7bd345109c1503425c77a3988b48df303c4f2573",
    "homepage": "http://waterlinejs.org",
    "keywords": [
        "mvc",
        "orm",
        "mysql",
        "postgresql",
        "redis",
        "mongodb",
        "active-record",
        "waterline",
        "sails",
        "sails.js"
    ],
    "license": "MIT",
    "main": "./lib/waterline",
    "maintainers": [
        {
            "name": "balderdashy",
            "email": "mike@balderdash.co"
        },
        {
            "name": "mikermcneil",
            "email": "michael.r.mcneil@gmail.com"
        },
        {
            "name": "particlebanana",
            "email": "particlebanana@gmail.com"
        },
        {
            "name": "sgress454",
            "email": "sgress454@treeline.io"
        }
    ],
    "name": "waterline",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/balderdashy/waterline.git"
    },
    "scripts": {
        "browserify": "rm -rf .dist && mkdir .dist && browserify lib/waterline.js -s Waterline | uglifyjs > .dist/waterline.min.js",
        "prepublish": "npm prune",
        "test": "make test"
    },
    "version": "0.11.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
