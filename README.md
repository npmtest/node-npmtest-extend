# npmtest-extend

#### test coverage for  [extend (v3.0.0)](https://github.com/justmoon/node-extend#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-extend.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-extend) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-extend.svg)](https://travis-ci.org/npmtest/node-npmtest-extend)

#### Port of jQuery.extend for node.js and the browser

[![NPM](https://nodei.co/npm/extend.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/extend)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-extend/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-extend/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-extend/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-extend/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-extend/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-extend/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-extend/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-extend/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-extend/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-extend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-extend/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-extend/build/test-report.html](https://npmtest.github.io/node-npmtest-extend/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-extend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-extend/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-extend/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-extend/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-extend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-extend/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-extend/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-extend/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stefan Thomas",
        "url": "http://www.justmoon.net"
    },
    "bugs": {
        "url": "https://github.com/justmoon/node-extend/issues"
    },
    "contributors": [
        {
            "name": "Jordan Harband",
            "url": "https://github.com/ljharb"
        }
    ],
    "dependencies": {},
    "description": "Port of jQuery.extend for node.js and the browser",
    "devDependencies": {
        "covert": "^1.1.0",
        "eslint": "^0.24.0",
        "jscs": "^1.13.1",
        "tape": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5a474353b9f3353ddd8176dfd37b91c83a46f1d4",
        "tarball": "https://registry.npmjs.org/extend/-/extend-3.0.0.tgz"
    },
    "gitHead": "148e7270cab2e9413af2cd0cab147070d755ed6d",
    "homepage": "https://github.com/justmoon/node-extend#readme",
    "keywords": [
        "extend",
        "clone",
        "merge"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "justmoon"
        },
        {
            "name": "ljharb"
        }
    ],
    "name": "extend",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/justmoon/node-extend.git"
    },
    "scripts": {
        "coverage": "covert test/index.js",
        "coverage-quiet": "covert test/index.js --quiet",
        "eslint": "eslint *.js */*.js",
        "jscs": "jscs *.js */*.js",
        "lint": "npm run jscs && npm run eslint",
        "test": "npm run lint && node test/index.js && npm run coverage-quiet"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
