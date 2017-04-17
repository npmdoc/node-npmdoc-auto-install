# api documentation for  [auto-install (v1.7.3)](https://github.com/siddharthkp/auto-install#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-auto-install.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-auto-install) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-auto-install.svg)](https://travis-ci.org/npmdoc/node-npmdoc-auto-install)
#### Auto installs dependencies as you code

[![NPM](https://nodei.co/npm/auto-install.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/auto-install)

- [https://npmdoc.github.io/node-npmdoc-auto-install/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-auto-install/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-auto-install/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-auto-install/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-auto-install/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-auto-install/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "siddharthkp"
    },
    "babel": {
        "presets": [
            "es2015"
        ]
    },
    "bin": {
        "auto-install": "lib/index.js"
    },
    "bugs": {
        "url": "https://github.com/siddharthkp/auto-install/issues"
    },
    "dependencies": {
        "chokidar": "1.6.1",
        "colors": "1.1.2",
        "detective": "4.3.2",
        "detective-es6": "1.1.5",
        "glob": "7.1.0",
        "is-builtin-module": "1.0.0",
        "log-symbols": "1.0.2",
        "ora": "0.3.0",
        "package-json": "2.4.0",
        "request": "2.74.0",
        "sync-exec": "0.6.2",
        "yargs": "6.3.0"
    },
    "description": "Auto installs dependencies as you code",
    "devDependencies": {
        "babel-cli": "6.14.0",
        "babel-preset-es2015": "6.14.0",
        "chai": "3.5.0",
        "eslint": "3.8.1",
        "eslint-config-airbnb": "12.0.0",
        "eslint-plugin-import": "1.16.0",
        "eslint-plugin-jsx-a11y": "2.2.3",
        "eslint-plugin-react": "6.4.1",
        "mocha": "3.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "85fb7c920a753a84b2c7a26242c9a65f546c5153",
        "tarball": "https://registry.npmjs.org/auto-install/-/auto-install-1.7.3.tgz"
    },
    "engines": {
        "node": ">= 4.4.5"
    },
    "gitHead": "46f16692933c72e1af9059686564690a2fe4ef45",
    "homepage": "https://github.com/siddharthkp/auto-install#readme",
    "keywords": [
        "auto",
        "dependencies",
        "install",
        "package",
        "watch"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "siddharthkp"
        }
    ],
    "name": "auto-install",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/siddharthkp/auto-install.git"
    },
    "scripts": {
        "build": "babel src -d lib && babel test/src -d test/lib",
        "lint": "eslint src",
        "run-tests": "cd example && mocha ../test/lib",
        "test": "npm run lint && npm run build && npm run run-tests"
    },
    "version": "1.7.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
