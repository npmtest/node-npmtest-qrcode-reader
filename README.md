# npmtest-qrcode-reader

#### test coverage for  [qrcode-reader (v0.2.2)](https://github.com/edi9999/jsqrcode)  [![npm package](https://img.shields.io/npm/v/npmtest-qrcode-reader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-qrcode-reader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-qrcode-reader.svg)](https://travis-ci.org/npmtest/node-npmtest-qrcode-reader)

#### fork of lazarsoft's jsqrcode for node

[![NPM](https://nodei.co/npm/qrcode-reader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/qrcode-reader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-qrcode-reader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-qrcode-reader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-qrcode-reader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-qrcode-reader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-qrcode-reader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-qrcode-reader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-qrcode-reader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-qrcode-reader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-qrcode-reader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-qrcode-reader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-qrcode-reader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-qrcode-reader/build/test-report.html](https://npmtest.github.io/node-npmtest-qrcode-reader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-qrcode-reader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-qrcode-reader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-qrcode-reader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-qrcode-reader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bugs": {
        "url": "https://github.com/edi9999/jsqrcode/issues"
    },
    "dependencies": {},
    "description": "fork of lazarsoft's jsqrcode for node",
    "devDependencies": {
        "chai": "^1.9.1",
        "eslint": "^2.13.1",
        "mocha": "^2.4.5",
        "png-js": "^0.1.1",
        "rollup": "^0.34.13",
        "uglify-js": "^2.7.3"
    },
    "directories": {},
    "dist": {
        "shasum": "1f202f2461d0eeed85e8794a6f44fe418dda7f87",
        "tarball": "https://registry.npmjs.org/qrcode-reader/-/qrcode-reader-0.2.2.tgz"
    },
    "gitHead": "c72886b18197be2dda5e3177cf033a73f430f0b7",
    "homepage": "https://github.com/edi9999/jsqrcode",
    "jsnext:main": "src/index.js",
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "edi9999"
        }
    ],
    "module": "src/index.js",
    "name": "qrcode-reader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/edi9999/jsqrcode.git"
    },
    "scripts": {
        "build": "rollup -c",
        "build-and-test": "npm run build && npm test",
        "lint": "eslint src test",
        "minify": "uglifyjs dist/index.js -o dist/index.min.js --compress --mangle",
        "prepublish": "npm run build && npm run minify",
        "pretest": "npm run lint",
        "test": "mocha",
        "watch": "rollup -c -w"
    },
    "version": "0.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
