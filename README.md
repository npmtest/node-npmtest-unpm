# npmtest-unpm

#### test coverage for  [unpm (v1.5.0)](https://github.com/hayes/unpm)  [![npm package](https://img.shields.io/npm/v/npmtest-unpm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-unpm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-unpm.svg)](https://travis-ci.org/npmtest/node-npmtest-unpm)

#### private npm registry in node

[![NPM](https://nodei.co/npm/unpm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/unpm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-unpm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-unpm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-unpm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-unpm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-unpm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-unpm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-unpm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-unpm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-unpm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-unpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-unpm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-unpm/build/test-report.html](https://npmtest.github.io/node-npmtest-unpm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-unpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-unpm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-unpm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-unpm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-unpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-unpm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-unpm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-unpm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Hayes"
    },
    "bin": {
        "unpm": "./bin/server.js"
    },
    "bugs": {
        "url": "https://github.com/hayes/unpm/issues"
    },
    "dependencies": {
        "bunyan": "^1.8.0",
        "concat-stream": "^1.4.6",
        "mkdirp": "^0.3.5",
        "nopt": "^2.2.1",
        "range_check": "1.2.0",
        "request": "^2.34.0",
        "semver": "^2.3.2",
        "unpm-auth": "^1.1.0",
        "unpm-fs-backend": "^0.1.0",
        "unpm-router": "^0.1.0"
    },
    "description": "private npm registry in node",
    "devDependencies": {
        "blanket": "1.1.6",
        "coveralls": "2.8.0",
        "jsl": "0.1.1",
        "mocha-lcov-reporter": "0.0.1",
        "tape": "2.5.0",
        "unpm-mem-backend": "0.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "31296708139c60ce5c3861c5ef71184e1957f80c",
        "tarball": "https://registry.npmjs.org/unpm/-/unpm-1.5.0.tgz"
    },
    "gitHead": "49622fabc1bec042aa268288291340558ffcc7d9",
    "homepage": "https://github.com/hayes/unpm",
    "keywords": [
        "npm",
        "private",
        "registry",
        "fnpm",
        "unpm",
        "package",
        "manager"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "hayes"
        },
        {
            "name": "jarofghosts"
        }
    ],
    "name": "unpm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hayes/unpm.git"
    },
    "scripts": {
        "coverage": "node scripts/coverage.js",
        "coveralls": "npm run coverage | ./node_modules/coveralls/bin/coveralls.js",
        "start": "node bin/server.js | bunyan",
        "test": "node ./test"
    },
    "version": "1.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
