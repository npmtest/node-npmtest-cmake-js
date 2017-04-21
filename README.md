# npmtest-cmake-js

#### basic test coverage for  cmake-js (v3.4.1)  [![npm package](https://img.shields.io/npm/v/npmtest-cmake-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cmake-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cmake-js.svg)](https://travis-ci.org/npmtest/node-npmtest-cmake-js)

#### CMake.js - a Node.js/io.js native addon build tool

[![NPM](https://nodei.co/npm/cmake-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cmake-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cmake-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cmake-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cmake-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cmake-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cmake-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cmake-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cmake-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cmake-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cmake-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cmake-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cmake-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cmake-js/build/test-report.html](https://npmtest.github.io/node-npmtest-cmake-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cmake-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cmake-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cmake-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cmake-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cmake-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cmake-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cmake-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cmake-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cmake-js",
    "description": "CMake.js - a Node.js/io.js native addon build tool",
    "license": "MIT",
    "keywords": [
        "native",
        "addon",
        "module",
        "c",
        "c++",
        "bindings",
        "build",
        "cmake",
        "nw.js",
        "electron",
        "boost"
    ],
    "version": "3.4.1",
    "author": "Gábor Mező aka unbornchikken",
    "repository": {
        "type": "git",
        "url": "git://github.com/unbornchikken/cmake-js.git"
    },
    "bin": "./bin/cmake-js",
    "engines": {
        "node": ">= 0.10.0"
    },
    "dependencies": {
        "bluebird": "^2.9.15",
        "debug": "^2.1.3",
        "fs-extra": "1",
        "is-iojs": "^1.0.1",
        "lodash": "^3.6.0",
        "memory-stream": "0",
        "npmconf": "^2.1.2",
        "npmlog": "^1.2.0",
        "request": "^2.54.0",
        "semver": "^5.0.3",
        "splitargs": "0",
        "tar": "^1.0.3",
        "traceur": "0.0.x",
        "unzip": "^0.1.11",
        "url-join": "0",
        "which": "^1.0.9",
        "yargs": "^3.6.0"
    },
    "devDependencies": {
        "gulp": "*",
        "gulp-sequence": "*",
        "gulp-sourcemaps": "*",
        "gulp-traceur": "*",
        "mocha": "*",
        "nan": "^2.1.0"
    },
    "scripts": {
        "test": "mocha tests",
        "compile": "gulp"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
