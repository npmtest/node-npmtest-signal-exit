# npmtest-signal-exit

#### basic test coverage for  [signal-exit (v3.0.2)](https://github.com/tapjs/signal-exit)  [![npm package](https://img.shields.io/npm/v/npmtest-signal-exit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-signal-exit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-signal-exit.svg)](https://travis-ci.org/npmtest/node-npmtest-signal-exit)

#### when you want to fire an event no matter how a process exits.

[![NPM](https://nodei.co/npm/signal-exit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/signal-exit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-signal-exit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-signal-exit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-signal-exit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-signal-exit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-signal-exit/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-signal-exit/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-signal-exit/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-signal-exit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-signal-exit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-signal-exit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-signal-exit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-signal-exit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-signal-exit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-signal-exit/build/test-report.html](https://npmtest.github.io/node-npmtest-signal-exit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-signal-exit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-signal-exit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-signal-exit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-signal-exit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-signal-exit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-signal-exit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-signal-exit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-signal-exit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Coe"
    },
    "bugs": {
        "url": "https://github.com/tapjs/signal-exit/issues"
    },
    "dependencies": {},
    "description": "when you want to fire an event no matter how a process exits.",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.10",
        "nyc": "^8.1.0",
        "standard": "^7.1.2",
        "standard-version": "^2.3.0",
        "tap": "^8.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b5fdc08f1287ea1178628e415e25132b73646c6d",
        "tarball": "https://registry.npmjs.org/signal-exit/-/signal-exit-3.0.2.tgz"
    },
    "files": [
        "index.js",
        "signals.js"
    ],
    "gitHead": "9c5ad9809fe6135ef22e2623989deaffe2a4fa8a",
    "homepage": "https://github.com/tapjs/signal-exit",
    "keywords": [
        "signal",
        "exit"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bcoe"
        },
        {
            "name": "isaacs"
        }
    ],
    "name": "signal-exit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tapjs/signal-exit.git"
    },
    "scripts": {
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "pretest": "standard",
        "release": "standard-version",
        "test": "tap --timeout=240 ./test/*.js --cov"
    },
    "version": "3.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
