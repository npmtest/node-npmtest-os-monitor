# npmtest-os-monitor

#### basic test coverage for  [os-monitor (v1.0.5)](https://github.com/lfortin/node-os-monitor)  [![npm package](https://img.shields.io/npm/v/npmtest-os-monitor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-os-monitor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-os-monitor.svg)](https://travis-ci.org/npmtest/node-npmtest-os-monitor)

#### simple OS monitoring for Node.js

[![NPM](https://nodei.co/npm/os-monitor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/os-monitor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-os-monitor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-os-monitor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-os-monitor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-os-monitor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-os-monitor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-os-monitor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-os-monitor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-os-monitor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-os-monitor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-os-monitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-os-monitor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-os-monitor/build/test-report.html](https://npmtest.github.io/node-npmtest-os-monitor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-os-monitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-os-monitor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-os-monitor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-os-monitor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-os-monitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-os-monitor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-os-monitor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-os-monitor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "os-monitor",
    "description": "simple OS monitoring for Node.js",
    "version": "1.0.5",
    "homepage": "https://github.com/lfortin/node-os-monitor",
    "repository": {
        "type": "git",
        "url": "git://github.com/lfortin/node-os-monitor.git"
    },
    "author": {
        "name": "Laurent Fortin",
        "url": "http://lfortin.github.io"
    },
    "main": "./os-monitor.js",
    "engines": {
        "node": ">=0.8.0"
    },
    "dependencies": {
        "readable-stream": "~2.1.5",
        "underscore": "~1.8.3"
    },
    "devDependencies": {
        "mock-os": "0.0.1"
    },
    "scripts": {
        "test": "node spec-runner.js"
    },
    "keywords": [
        "monitor",
        "os"
    ],
    "license": "MIT",
    "optionalDependencies": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
