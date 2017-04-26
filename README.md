# npmtest-he

#### basic test coverage for  [he (v1.1.1)](https://mths.be/he)  [![npm package](https://img.shields.io/npm/v/npmtest-he.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-he) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-he.svg)](https://travis-ci.org/npmtest/node-npmtest-he)

#### A robust HTML entities encoder/decoder with full Unicode support.

[![NPM](https://nodei.co/npm/he.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/he)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-he/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-he/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-he/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-he/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-he/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-he/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-he/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-he/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-he/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-he/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-he/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-he/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-he/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-he/build/test-report.html](https://npmtest.github.io/node-npmtest-he/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-he/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-he/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-he/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-he/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-he/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-he/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-he/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-he/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Bynens",
        "url": "https://mathiasbynens.be/"
    },
    "bin": {
        "he": "bin/he"
    },
    "bugs": {
        "url": "https://github.com/mathiasbynens/he/issues"
    },
    "dependencies": {},
    "description": "A robust HTML entities encoder/decoder with full Unicode support.",
    "devDependencies": {
        "codecov.io": "^0.1.6",
        "grunt": "^0.4.5",
        "grunt-shell": "^1.1.1",
        "grunt-template": "^0.2.3",
        "istanbul": "^0.4.2",
        "jsesc": "^1.0.0",
        "lodash": "^4.8.2",
        "qunit-extras": "^1.4.5",
        "qunitjs": "~1.11.0",
        "regenerate": "^1.2.1",
        "requirejs": "^2.1.22",
        "sort-object": "^3.0.2"
    },
    "directories": {
        "bin": "bin",
        "man": "man",
        "test": "tests"
    },
    "dist": {
        "shasum": "93410fd21b009735151f8868c2f271f3427e23fd",
        "tarball": "https://registry.npmjs.org/he/-/he-1.1.1.tgz"
    },
    "files": [
        "LICENSE-MIT.txt",
        "he.js",
        "bin/",
        "man/"
    ],
    "gitHead": "670991a4141d01dc015de5194d400d01c863208f",
    "homepage": "https://mths.be/he",
    "keywords": [
        "string",
        "entities",
        "entity",
        "html",
        "encode",
        "decode",
        "unicode"
    ],
    "license": "MIT",
    "main": "he.js",
    "maintainers": [
        {
            "name": "mathias"
        }
    ],
    "man": [
        "/private/tmp/he/man/he.1"
    ],
    "name": "he",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mathiasbynens/he.git"
    },
    "scripts": {
        "build": "grunt build",
        "test": "node tests/tests.js"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
