# npmtest-timediff

#### basic test coverage for  [timediff (v1.1.1)](https://github.com/marcotaubmann/timediff)  [![npm package](https://img.shields.io/npm/v/npmtest-timediff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-timediff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-timediff.svg)](https://travis-ci.org/npmtest/node-npmtest-timediff)

#### Calculate a time difference in several time units.

[![NPM](https://nodei.co/npm/timediff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/timediff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-timediff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-timediff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-timediff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-timediff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-timediff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-timediff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-timediff/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-timediff/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-timediff/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-timediff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-timediff/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-timediff/build/test-report.html](https://npmtest.github.io/node-npmtest-timediff/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-timediff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-timediff/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-timediff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-timediff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-timediff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-timediff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-timediff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-timediff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "timediff",
    "version": "1.1.1",
    "description": "Calculate a time difference in several time units.",
    "author": "Marco Taubmann",
    "license": "MIT",
    "main": "timediff.js",
    "engines": {
        "node": ">=0.10.0"
    },
    "bin": {
        "timediff": "cli.js"
    },
    "scripts": {
        "test": "node_modules/jasmine-node/bin/jasmine-node test/"
    },
    "keywords": [
        "time",
        "moment",
        "date",
        "diff"
    ],
    "homepage": "https://github.com/marcotaubmann/timediff",
    "bugs": {
        "url": "https://github.com/marcotaubmann/timediff/issues"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/marcotaubmann/timediff"
    },
    "dependencies": {
        "moment": "^2.9.0"
    },
    "devDependencies": {
        "jasmine-node": "^1.14.5"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
