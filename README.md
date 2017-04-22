# npmtest-dotenv-safe

#### basic test-coverage for  [dotenv-safe (v4.0.3)](https://github.com/rolodato/dotenv-safe#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-dotenv-safe.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dotenv-safe) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dotenv-safe.svg)](https://travis-ci.org/npmtest/node-npmtest-dotenv-safe)

#### Load environment variables from .env and ensure they are defined

[![NPM](https://nodei.co/npm/dotenv-safe.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dotenv-safe)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dotenv-safe/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dotenv-safe/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dotenv-safe/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dotenv-safe/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dotenv-safe/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dotenv-safe/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dotenv-safe/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dotenv-safe/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dotenv-safe/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dotenv-safe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dotenv-safe/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dotenv-safe/build/test-report.html](https://npmtest.github.io/node-npmtest-dotenv-safe/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dotenv-safe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dotenv-safe/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dotenv-safe/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dotenv-safe/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dotenv-safe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dotenv-safe/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dotenv-safe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dotenv-safe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rodrigo López Dato"
    },
    "bugs": {
        "url": "https://github.com/rolodato/dotenv-safe/issues"
    },
    "dependencies": {
        "dotenv": "^4.0.0"
    },
    "description": "Load environment variables from .env and ensure they are defined",
    "devDependencies": {
        "chai": "^3.5.0",
        "eslint": "^3.12.2",
        "fs-extra": "^1.0.0",
        "lodash.clonedeep": "^4.5.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "3c98f69f6072f7b2d0df120a65add27ac2550029",
        "tarball": "https://registry.npmjs.org/dotenv-safe/-/dotenv-safe-4.0.3.tgz"
    },
    "files": [
        "index.js",
        "config.js",
        "MissingEnvVarsError.js"
    ],
    "gitHead": "a6dab2b8184aa4af171cccaf5327cdeed387d536",
    "homepage": "https://github.com/rolodato/dotenv-safe#readme",
    "keywords": [
        "dotenv"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rolodato"
        }
    ],
    "name": "dotenv-safe",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/rolodato/dotenv-safe.git"
    },
    "scripts": {
        "pretest": "./node_modules/eslint/bin/eslint.js index.js config.js MissingEnvVarsError.js test/.",
        "test": "HELLO=fromTheOtherSide mocha"
    },
    "version": "4.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
