# npmtest-wscat

#### basic test coverage for  wscat (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-wscat.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wscat) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wscat.svg)](https://travis-ci.org/npmtest/node-npmtest-wscat)

#### WebSocket cat

[![NPM](https://nodei.co/npm/wscat.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wscat)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wscat/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wscat/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wscat/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wscat/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wscat/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-wscat/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-wscat/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wscat/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wscat/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wscat/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wscat/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wscat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wscat/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wscat/build/test-report.html](https://npmtest.github.io/node-npmtest-wscat/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wscat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wscat/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wscat/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wscat/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wscat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wscat/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wscat/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wscat/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "wscat",
    "version": "2.0.0",
    "description": "WebSocket cat",
    "main": "index.js",
    "scripts": {
        "test": "echo \"No test specified\""
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/websockets/wscat"
    },
    "keywords": [
        "wscat",
        "websocket",
        "cat"
    ],
    "author": "Arnout Kazemier, Einar Otto Stangvik",
    "license": "MIT",
    "dependencies": {
        "commander": "~2.9.0",
        "read": "~1.0.7",
        "tinycolor": "~0.0.1",
        "ws": "~2.1.0"
    },
    "bin": {
        "wscat": "./bin/wscat"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
