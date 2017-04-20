# npmtest-json-diff

#### basic test coverage for  [json-diff (v0.3.1)](https://github.com/andreyvit/json-diff)  [![npm package](https://img.shields.io/npm/v/npmtest-json-diff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-json-diff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-json-diff.svg)](https://travis-ci.org/npmtest/node-npmtest-json-diff)

#### JSON diff

[![NPM](https://nodei.co/npm/json-diff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json-diff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-json-diff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-diff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-json-diff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-json-diff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-json-diff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-json-diff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-json-diff/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-json-diff/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-json-diff/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-json-diff/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-json-diff/build/test-report.html](https://npmtest.github.io/node-npmtest-json-diff/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-json-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-json-diff/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-json-diff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json-diff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json-diff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-json-diff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-json-diff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Andrey Tarantsov <andreyvit@me.com>",
    "name": "json-diff",
    "description": "JSON diff",
    "version": "0.3.1",
    "homepage": "https://github.com/andreyvit/json-diff",
    "repository": {
        "url": "git@github.com:andreyvit/json-diff.git"
    },
    "main": "lib/index.js",
    "bin": "bin/json-diff.js",
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha",
        "cov": "rm -rf lib-cov; jscoverage lib lib-cov; env JSLIB=lib-cov mocha -R dot && env JSLIB=lib-cov mocha -R html-cov >coverage.html; open coverage.html"
    },
    "dependencies": {
        "dreamopt": "~0.6.0",
        "difflib": "~0.2.1",
        "cli-color": "~0.1.6"
    },
    "devDependencies": {
        "mocha": "~1.7.0"
    },
    "optionalDependencies": {},
    "engines": {
        "node": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
