# npmtest-isstream

#### basic test coverage for  [isstream (v0.1.2)](https://github.com/rvagg/isstream)  [![npm package](https://img.shields.io/npm/v/npmtest-isstream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-isstream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-isstream.svg)](https://travis-ci.org/npmtest/node-npmtest-isstream)

#### Determine if an object is a Stream

[![NPM](https://nodei.co/npm/isstream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/isstream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-isstream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-isstream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-isstream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-isstream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-isstream/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-isstream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-isstream/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-isstream/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-isstream/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-isstream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-isstream/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-isstream/build/test-report.html](https://npmtest.github.io/node-npmtest-isstream/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-isstream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-isstream/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-isstream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-isstream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-isstream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-isstream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-isstream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-isstream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "isstream",
    "version": "0.1.2",
    "description": "Determine if an object is a Stream",
    "main": "isstream.js",
    "scripts": {
        "test": "tar --xform 's/^package/readable-stream-1.0/' -zxf readable-stream-1.0.*.tgz && tar --xform 's/^package/readable-stream-1.1/' -zxf readable-stream-1.1.*.tgz && node test.js; rm -rf readable-stream-1.?/"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/rvagg/isstream.git"
    },
    "keywords": [
        "stream",
        "type",
        "streams",
        "readable-stream",
        "hippo"
    ],
    "devDependencies": {
        "tape": "~2.12.3",
        "core-util-is": "~1.0.0",
        "isarray": "0.0.1",
        "string_decoder": "~0.10.x",
        "inherits": "~2.0.1"
    },
    "author": "Rod Vagg <rod@vagg.org>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/rvagg/isstream/issues"
    },
    "homepage": "https://github.com/rvagg/isstream"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
