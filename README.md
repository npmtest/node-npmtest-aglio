# test coverage for  [aglio (v2.3.0)](https://github.com/danielgtaylor/aglio#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-aglio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-aglio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-aglio.svg)](https://travis-ci.org/npmtest/node-npmtest-aglio)
#### An API Blueprint renderer with theme support

[![NPM](https://nodei.co/npm/aglio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aglio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-aglio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-aglio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-aglio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-aglio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-aglio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-aglio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-aglio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-aglio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-aglio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-aglio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-aglio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-aglio/build/test-report.html](https://npmtest.github.io/node-npmtest-aglio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-aglio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-aglio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-aglio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aglio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aglio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aglio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-aglio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-aglio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel G. Taylor"
    },
    "bin": {
        "aglio": "./bin/aglio.js"
    },
    "bugs": {
        "url": "https://github.com/danielgtaylor/aglio/issues"
    },
    "dependencies": {
        "aglio-theme-olio": "^1.6.3",
        "chokidar": "^1.4.1",
        "cli-color": "^1.1.0",
        "drafter": "^1.0.0",
        "pretty-error": "^1.2.0",
        "serve-static": "^1.10.0",
        "socket.io": "^1.3.7",
        "yargs": "^3.31.0"
    },
    "description": "An API Blueprint renderer with theme support",
    "devDependencies": {
        "async": "^1.5.0",
        "coffeelint": "^1.14.2",
        "grunt": "~0.4.5",
        "grunt-coffeelint": "0.0.13",
        "grunt-contrib-coffee": "^0.13.0",
        "grunt-mocha-cov": "^0.4.0",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "9f7462f01520996415278a02d0e20b36ec96adcc",
        "tarball": "https://registry.npmjs.org/aglio/-/aglio-2.3.0.tgz"
    },
    "gitHead": "df554dc380c0ee6a2c83f8c62c4739491c5dd3c2",
    "homepage": "https://github.com/danielgtaylor/aglio#readme",
    "keywords": [
        "api",
        "blueprint",
        "protagonist",
        "snowcrash",
        "html",
        "parse",
        "markdown"
    ],
    "license": "MIT",
    "main": "lib/main.js",
    "maintainers": [
        {
            "name": "danielgtaylor"
        },
        {
            "name": "zdne"
        },
        {
            "name": "pksunkara"
        },
        {
            "name": "kylef"
        }
    ],
    "name": "aglio",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/danielgtaylor/aglio.git"
    },
    "scripts": {
        "prepublish": "grunt compile",
        "test": "grunt test"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
