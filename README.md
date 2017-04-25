# npmtest-asyncawait

#### basic test coverage for  [asyncawait (v1.0.6)](https://github.com/yortus/asyncawait)  [![npm package](https://img.shields.io/npm/v/npmtest-asyncawait.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-asyncawait) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-asyncawait.svg)](https://travis-ci.org/npmtest/node-npmtest-asyncawait)

#### async/await for node.js

[![NPM](https://nodei.co/npm/asyncawait.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/asyncawait)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-asyncawait/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-asyncawait/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-asyncawait/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-asyncawait/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-asyncawait/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-asyncawait/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-asyncawait/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-asyncawait/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-asyncawait/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-asyncawait/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-asyncawait/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-asyncawait/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-asyncawait/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-asyncawait/build/test-report.html](https://npmtest.github.io/node-npmtest-asyncawait/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-asyncawait/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-asyncawait/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-asyncawait/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-asyncawait/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-asyncawait/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-asyncawait/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-asyncawait/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-asyncawait/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Troy Gerwien",
        "url": "http://github.com/yortus/"
    },
    "bugs": {
        "url": "http://github.com/yortus/asyncawait/issues"
    },
    "dependencies": {
        "bluebird": "^3.1.1",
        "fibers": "^1.0.8",
        "lodash": "v3.10.1"
    },
    "description": "async/await for node.js",
    "devDependencies": {
        "async": "^1.4.2",
        "asyncx": "^0.4.5",
        "chai": "^3.2.0",
        "co": "^4.6.0",
        "mocha": "^2.3.2",
        "mock-fs": "^3.1.0",
        "rewire": "^2.3.4",
        "typescript": "1.7.5"
    },
    "directories": {},
    "dist": {
        "shasum": "e446cf54e516a416d7423bbe35bf0b4e2b738b67",
        "tarball": "https://registry.npmjs.org/asyncawait/-/asyncawait-1.0.6.tgz"
    },
    "gitHead": "f9e865c42f3efa6844717bdd71d33b1039ed5d24",
    "homepage": "https://github.com/yortus/asyncawait",
    "keywords": [
        "async/await",
        "async",
        "await",
        "yield",
        "control flow",
        "coroutine",
        "generator",
        "callback",
        "callback hell",
        "pyramid of doom",
        "fiber",
        "typescript",
        "coffeescript",
        "asynchronous",
        "synchronous"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "yortus"
        }
    ],
    "name": "asyncawait",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/yortus/asyncawait.git"
    },
    "scripts": {
        "build": "tsc",
        "prepublish": "npm run build",
        "test": "mocha"
    },
    "version": "1.0.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
