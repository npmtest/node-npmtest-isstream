# npmtest-isstream

#### basic test coverage for  [isstream (v0.1.2)](https://github.com/rvagg/isstream)  [![npm package](https://img.shields.io/npm/v/npmtest-isstream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-isstream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-isstream.svg)](https://travis-ci.org/npmtest/node-npmtest-isstream)

#### Determine if an object is a Stream

[![NPM](https://nodei.co/npm/isstream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/isstream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-isstream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-isstream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-isstream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-isstream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-isstream/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-isstream/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-isstream/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-isstream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-isstream/tree/gh-pages/build)|

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
    "author": {
        "name": "Rod Vagg"
    },
    "bugs": {
        "url": "https://github.com/rvagg/isstream/issues"
    },
    "dependencies": {},
    "description": "Determine if an object is a Stream",
    "devDependencies": {
        "core-util-is": "~1.0.0",
        "inherits": "~2.0.1",
        "isarray": "0.0.1",
        "string_decoder": "~0.10.x",
        "tape": "~2.12.3"
    },
    "directories": {},
    "dist": {
        "shasum": "47e63f7af55afa6f92e1500e690eb8b8529c099a",
        "tarball": "https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz"
    },
    "gitHead": "cd39cba6da939b4fc9110825203adc506422c3dc",
    "homepage": "https://github.com/rvagg/isstream",
    "keywords": [
        "stream",
        "type",
        "streams",
        "readable-stream",
        "hippo"
    ],
    "license": "MIT",
    "main": "isstream.js",
    "maintainers": [
        {
            "name": "rvagg"
        }
    ],
    "name": "isstream",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rvagg/isstream.git"
    },
    "scripts": {
        "test": "tar --xform 's/^package/readable-stream-1.0/' -zxf readable-stream-1.0.*.tgz && tar --xform 's/^package/readable-stream-1.1/' -zxf readable-stream-1.1.*.tgz && node test.js; rm -rf readable-stream-1.?/"
    },
    "version": "0.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
