# npmtest-gulp-minify-inline

#### basic test coverage for  [gulp-minify-inline (v0.2.1)](https://github.com/shkuznetsov/gulp-minify-inline)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-minify-inline.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-minify-inline) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-minify-inline.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-minify-inline)

#### Gulp plugin to uglify inline JS and minify inline CSS

[![NPM](https://nodei.co/npm/gulp-minify-inline.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-minify-inline)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-minify-inline/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-minify-inline/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-minify-inline/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-minify-inline/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-minify-inline/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-minify-inline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-minify-inline/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-minify-inline/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-minify-inline",
    "description": "Gulp plugin to uglify inline JS and minify inline CSS",
    "version": "0.2.1",
    "author": {
        "name": "Alexander Kuznetsov",
        "url": "http://kuznetsov.by/"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/shkuznetsov/gulp-minify-inline.git"
    },
    "homepage": "https://github.com/shkuznetsov/gulp-minify-inline",
    "keywords": [
        "gulpplugin",
        "uglify",
        "minify",
        "inline",
        "js",
        "javascript",
        "script",
        "css",
        "style"
    ],
    "main": "./index.js",
    "dependencies": {
        "gulp-util": "^3.0.7",
        "cheerio": "^0.20.0",
        "uglify-js": "^2.6.2",
        "clean-css": "^3.4.12",
        "through2": "^2.0.1"
    },
    "devDependencies": {
        "gulp": "~3.9.1",
        "chai": "~3.5.0",
        "mocha": "~2.4.5"
    },
    "scripts": {
        "test": "mocha"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "license": "MIT",
    "readmeFilename": "README.md",
    "bugs": {
        "url": "https://github.com/shkuznetsov/gulp-minify-inline/issues"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
