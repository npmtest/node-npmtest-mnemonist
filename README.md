# npmtest-mnemonist

#### basic test coverage for  [mnemonist (v0.12.0)](https://github.com/yomguithereal/mnemonist#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mnemonist.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mnemonist) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mnemonist.svg)](https://travis-ci.org/npmtest/node-npmtest-mnemonist)

#### Curated collection of data structures for the JavaScript language.

[![NPM](https://nodei.co/npm/mnemonist.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mnemonist)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mnemonist/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mnemonist/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mnemonist/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mnemonist/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mnemonist/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mnemonist/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mnemonist/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mnemonist/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mnemonist/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mnemonist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mnemonist/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mnemonist/build/test-report.html](https://npmtest.github.io/node-npmtest-mnemonist/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mnemonist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mnemonist/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mnemonist/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mnemonist/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mnemonist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mnemonist/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mnemonist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mnemonist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Guillaume Plique",
        "url": "http://github.com/Yomguithereal"
    },
    "bugs": {
        "url": "https://github.com/yomguithereal/mnemonist/issues"
    },
    "dependencies": {},
    "description": "Curated collection of data structures for the JavaScript language.",
    "devDependencies": {
        "@yomguithereal/eslint-config": "^3.0.0",
        "damerau-levenshtein": "^1.0.3",
        "eslint": "^3.8.1",
        "leven": "^2.0.0",
        "lodash": "^4.17.4",
        "mocha": "^3.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5ff78f86cf0d28a28e1fb8e4f514469b4e78cc1b",
        "tarball": "https://registry.npmjs.org/mnemonist/-/mnemonist-0.12.0.tgz"
    },
    "eslintConfig": {
        "extends": "@yomguithereal/eslint-config",
        "globals": {
            "Set": true,
            "Map": true,
            "Symbol": true,
            "Uint8Array": true,
            "Uint16Array": true,
            "Float64Array": true
        },
        "parserOptions": {
            "ecmaVersion": 6
        },
        "ecmaFeatures": {
            "forOf": true
        }
    },
    "files": [
        "utils",
        "*.js"
    ],
    "gitHead": "6429f0279e8dd8e9cff0191c47deb96a6696412c",
    "homepage": "https://github.com/yomguithereal/mnemonist#readme",
    "keywords": [
        "data structures",
        "structures",
        "heap",
        "fibonacci heap",
        "stack",
        "queue",
        "inverted index",
        "linked list",
        "trie",
        "bag",
        "multiset",
        "multimap",
        "counter",
        "suffix tree",
        "symspell",
        "bk tree",
        "burkhard-keller tree",
        "vp tree",
        "vantage point tree"
    ],
    "license": "MIT",
    "main": "endpoint.js",
    "maintainers": [
        {
            "name": "yomguithereal"
        }
    ],
    "name": "mnemonist",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yomguithereal/mnemonist.git"
    },
    "scripts": {
        "lint": "eslint ./*.js ./utils ./test",
        "prepublish": "npm run lint && npm test",
        "test": "mocha"
    },
    "version": "0.12.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
