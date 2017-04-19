# npmtest-browserify-transform-tools

#### test coverage for  [browserify-transform-tools (v1.7.0)](https://github.com/benbria/browserify-transform-tools#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-browserify-transform-tools.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-browserify-transform-tools) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-browserify-transform-tools.svg)](https://travis-ci.org/npmtest/node-npmtest-browserify-transform-tools)

#### Utilities for writing browserify transforms.

[![NPM](https://nodei.co/npm/browserify-transform-tools.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browserify-transform-tools)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-browserify-transform-tools/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-browserify-transform-tools/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-browserify-transform-tools/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/test-report.html](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-browserify-transform-tools/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browserify-transform-tools/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browserify-transform-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browserify-transform-tools/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-browserify-transform-tools/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Walton",
        "url": "https://github.com/jwalton"
    },
    "bugs": {
        "url": "https://github.com/benbria/browserify-transform-tools/issues"
    },
    "contributors": [
        {
            "name": "Jason Walton",
            "url": "https://github.com/jwalton"
        }
    ],
    "dependencies": {
        "falafel": "^2.0.0",
        "through": "^2.3.7"
    },
    "description": "Utilities for writing browserify transforms.",
    "devDependencies": {
        "browserify": "^10.1.0",
        "chai": "^2.3.0",
        "coffee-coverage": "^0.5.4",
        "coffee-script": "^1.9.2",
        "coveralls": "^2.11.2",
        "es6-promise": "^2.1.1",
        "istanbul": "^0.3.14",
        "mocha": "^2.2.4"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "83e277221f63259bed2e7eb2a283a970a501f4c4",
        "tarball": "https://registry.npmjs.org/browserify-transform-tools/-/browserify-transform-tools-1.7.0.tgz"
    },
    "gitHead": "66497a5171ad8b5ce3a5ab6907dbde5755804f3e",
    "homepage": "https://github.com/benbria/browserify-transform-tools#readme",
    "keywords": [
        "browserify",
        "transform",
        "utilities"
    ],
    "license": "MIT",
    "main": "./lib/transformTools.js",
    "maintainers": [
        {
            "name": "jwalton"
        },
        {
            "name": "kreisys"
        },
        {
            "name": "metelyk"
        }
    ],
    "name": "browserify-transform-tools",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/benbria/browserify-transform-tools.git"
    },
    "scripts": {
        "build": "coffee -c -o lib src",
        "prepublish": "coffee -c -o lib src && npm test",
        "test": "mocha && istanbul report text-summary lcov"
    },
    "version": "1.7.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
