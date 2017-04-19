# npmtest-napa

#### test coverage for  [napa (v2.3.0)](https://github.com/shama/napa)  [![npm package](https://img.shields.io/npm/v/npmtest-napa.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-napa) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-napa.svg)](https://travis-ci.org/npmtest/node-npmtest-napa)

#### A helper for installing repos without a package.json with npm.

[![NPM](https://nodei.co/npm/napa.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/napa)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-napa/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-napa/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-napa/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-napa/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-napa/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-napa/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-napa/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-napa/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-napa/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-napa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-napa/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-napa/build/test-report.html](https://npmtest.github.io/node-npmtest-napa/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-napa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-napa/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-napa/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-napa/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-napa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-napa/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-napa/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-napa/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Robinson Young",
        "url": "http://dontkry.com"
    },
    "bin": {
        "napa": "bin/napa"
    },
    "bugs": {
        "url": "https://github.com/shama/napa/issues"
    },
    "dependencies": {
        "download": "^4.4.1",
        "extend": "^3.0.0",
        "load-json-file": "^1.1.0",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.0",
        "npm-cache-filename": "^1.0.1",
        "npmlog": "^2.0.2",
        "rimraf": "^2.5.1",
        "tar-pack": "^3.1.2",
        "write-json-file": "^1.2.0"
    },
    "description": "A helper for installing repos without a package.json with npm.",
    "devDependencies": {
        "codeclimate-test-reporter": "^0.3.0",
        "istanbul": "^0.4.2",
        "pre-commit": "^1.1.1",
        "standard": "^5.4.1",
        "tape": "^4.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4196546d1a0b6bb94f37042053cc5ddd79731e53",
        "tarball": "https://registry.npmjs.org/napa/-/napa-2.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "4bfe0bdb513ffa869a79ddcd3fec1b0874d2b35f",
    "homepage": "https://github.com/shama/napa",
    "keywords": [
        "npm",
        "install",
        "assets"
    ],
    "license": "MIT",
    "main": "lib/pkg.js",
    "maintainers": [
        {
            "name": "caseywebb"
        },
        {
            "name": "shama"
        },
        {
            "name": "tomekwi"
        }
    ],
    "name": "napa",
    "napa": {
        "foo": "foo/repo",
        "ember": "https://github.com/emberjs/ember.js/archive/v1.7.0.tar.gz",
        "handlebars": "components/handlebars.js"
    },
    "napa-config": {
        "cache": false
    },
    "optionalDependencies": {},
    "pre-commit": [
        "format"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/shama/napa.git"
    },
    "scripts": {
        "coverage": "istanbul report html && open ./coverage/index.html",
        "format": "standard",
        "test": "istanbul cover --report lcov --print detail test.js"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
