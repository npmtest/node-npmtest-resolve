# npmtest-resolve

#### basic test coverage for  [resolve (v1.3.3)](https://github.com/substack/node-resolve#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-resolve.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-resolve) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-resolve.svg)](https://travis-ci.org/npmtest/node-npmtest-resolve)

#### resolve like require.resolve() on behalf of files asynchronously and synchronously

[![NPM](https://nodei.co/npm/resolve.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/resolve)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-resolve/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-resolve/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-resolve/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-resolve/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-resolve/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-resolve/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-resolve/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-resolve/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-resolve/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-resolve/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-resolve/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-resolve/build/test-report.html](https://npmtest.github.io/node-npmtest-resolve/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-resolve/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-resolve/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-resolve/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-resolve/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-resolve/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-resolve/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-resolve/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-resolve/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/node-resolve/issues"
    },
    "dependencies": {
        "path-parse": "^1.0.5"
    },
    "description": "resolve like require.resolve() on behalf of files asynchronously and synchronously",
    "devDependencies": {
        "@ljharb/eslint-config": "^11.0.0",
        "eslint": "^3.19.0",
        "object-keys": "^1.0.11",
        "safe-publish-latest": "^1.1.1",
        "tap": "0.4.13",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "655907c3469a8680dc2de3a275a8fdd69691f0e5",
        "tarball": "https://registry.npmjs.org/resolve/-/resolve-1.3.3.tgz"
    },
    "gitHead": "f0098226a4fd0dedc85b5f1e8ca8aac6a7ca7a60",
    "homepage": "https://github.com/substack/node-resolve#readme",
    "keywords": [
        "resolve",
        "require",
        "node",
        "module"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ljharb"
        },
        {
            "name": "substack"
        }
    ],
    "name": "resolve",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/node-resolve.git"
    },
    "scripts": {
        "lint": "eslint .",
        "prepublish": "safe-publish-latest",
        "pretest": "npm run lint",
        "test": "npm run --silent tests-only",
        "tests-only": "tape test/*.js"
    },
    "version": "1.3.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
