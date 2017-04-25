# npmtest-node-gd

#### basic test coverage for  [node-gd (v1.5.0)](https://github.com/y-a-v-a/node-gd)  [![npm package](https://img.shields.io/npm/v/npmtest-node-gd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-gd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-gd.svg)](https://travis-ci.org/npmtest/node-npmtest-node-gd)

#### GD graphics library (libgd) C++ bindings for Node.js

[![NPM](https://nodei.co/npm/node-gd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-gd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-gd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-gd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-gd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-gd/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-gd/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-gd/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-gd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-gd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-gd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-gd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-gd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-gd/build/test-report.html](https://npmtest.github.io/node-npmtest-node-gd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-gd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-gd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-gd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-gd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-gd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-gd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-gd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-gd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-gd",
    "version": "1.5.0",
    "description": "GD graphics library (libgd) C++ bindings for Node.js",
    "main": "js/node-gd.js",
    "directories": {
        "test": "test"
    },
    "os": [
        "!win32"
    ],
    "homepage": "https://github.com/y-a-v-a/node-gd",
    "bugs": "https://github.com/y-a-v-a/node-gd/issues",
    "scripts": {
        "pretest": "node-gyp rebuild",
        "test": "mocha --expose-gc --reporter spec --bail --ui bdd --colors",
        "install": "node-gyp rebuild",
        "update-contributors": "git shortlog -s -e -n>CONTRIBUTORS.md"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/y-a-v-a/node-gd.git"
    },
    "keywords": [
        "libgd",
        "libgd2",
        "gd",
        "image",
        "png",
        "jpg",
        "jpeg",
        "gif",
        "graphics",
        "library"
    ],
    "author": "Taegon Kim <gonom9@gmail.com>",
    "license": "MIT",
    "contributors": [
        {
            "name": "Dudochkin Victor"
        },
        {
            "name": "Andris Reinman"
        },
        {
            "name": "Peter Magnusson"
        },
        {
            "name": "Damian Senn"
        },
        {
            "name": "Farrin Reid"
        },
        {
            "name": "Josh (zer0x304)"
        },
        {
            "name": "Mike Smullin"
        },
        {
            "name": "Vincent Bruijn (y_a_v_a)"
        }
    ],
    "gypfile": true,
    "readmeFilename": "README.md",
    "devDependencies": {
        "chai": "3.5.0",
        "mocha": "2.4.5"
    },
    "dependencies": {
        "node-gyp": "3.6.0",
        "nan": "2.5.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
