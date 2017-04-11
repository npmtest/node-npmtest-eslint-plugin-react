# test coverage for  [eslint-plugin-react (v6.10.3)](https://github.com/yannickcr/eslint-plugin-react)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-react.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-react.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-react)
#### React specific linting rules for ESLint

[![NPM](https://nodei.co/npm/eslint-plugin-react.png?downloads=true)](https://www.npmjs.com/package/eslint-plugin-react)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-react/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-react/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-react/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-eslint-plugin-react%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-react/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-eslint-plugin-react%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-react/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-react/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yannick Croissant",
        "email": "yannick.croissant+npm@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/yannickcr/eslint-plugin-react/issues"
    },
    "dependencies": {
        "array.prototype.find": "^2.0.1",
        "doctrine": "^1.2.2",
        "has": "^1.0.1",
        "jsx-ast-utils": "^1.3.4",
        "object.assign": "^4.0.4"
    },
    "description": "React specific linting rules for ESLint",
    "devDependencies": {
        "babel-eslint": "7.1.1",
        "coveralls": "2.11.15",
        "eslint": "^2.0.0 || ^3.0.0",
        "istanbul": "0.4.5",
        "mocha": "3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c5435beb06774e12c7db2f6abaddcbf900cd3f78",
        "tarball": "https://registry.npmjs.org/eslint-plugin-react/-/eslint-plugin-react-6.10.3.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "LICENSE",
        "README.md",
        "index.js",
        "lib"
    ],
    "gitHead": "b9cfdd6fccedd8c3ad1d2db334574bba38a1aaf8",
    "homepage": "https://github.com/yannickcr/eslint-plugin-react",
    "keywords": [
        "eslint",
        "eslint-plugin",
        "eslintplugin",
        "react"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "yannickcr",
            "email": "yannick.croissant+npm@gmail.com"
        }
    ],
    "name": "eslint-plugin-react",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "^2.0.0 || ^3.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yannickcr/eslint-plugin-react.git"
    },
    "scripts": {
        "coveralls": "cat ./reports/coverage/lcov.info | coveralls",
        "lint": "eslint ./",
        "test": "npm run lint && npm run unit-test",
        "unit-test": "istanbul cover --dir reports/coverage node_modules/mocha/bin/_mocha tests/**/*.js -- --reporter dot --opts tests/mocha.opts"
    },
    "version": "6.10.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
