# npmdoc-i18n-express

#### api documentation for  [i18n-express (v1.1.2)](https://github.com/koalazak/i18n-express)  [![npm package](https://img.shields.io/npm/v/npmdoc-i18n-express.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-i18n-express) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-i18n-express.svg)](https://travis-ci.org/npmdoc/node-npmdoc-i18n-express)

#### A simple i18n middleware for Express.js.

[![NPM](https://nodei.co/npm/i18n-express.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/i18n-express)

- [https://npmdoc.github.io/node-npmdoc-i18n-express/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-i18n-express/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-i18n-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-i18n-express/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-i18n-express/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-i18n-express/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "i18n-express",
    "version": "1.1.2",
    "description": "A simple i18n middleware for Express.js.",
    "main": "index.js",
    "scripts": {
        "pretest": "npm install",
        "check:style": "eslint .",
        "test": "_mocha -- $npm_package_config_mocha && npm run check:style && npm run test:coverage",
        "test:coverage:run": "istanbul cover _mocha -- $npm_package_config_mocha",
        "test:coverage:check": "istanbul check-coverage --functions 80",
        "test:coverage": "npm run test:coverage:run && npm run test:coverage:check"
    },
    "devDependencies": {
        "mocha": "^3.1.2",
        "istanbul": "^0.4.0",
        "semistandard": "^9.1.0",
        "eslint": "^3.8.0",
        "eslint-config-standard": "^6.2.0",
        "eslint-config-semistandard": "^7.0.0",
        "eslint-plugin-promise": "^3.0.0",
        "eslint-plugin-standard": "^2.0.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/koalazak/i18n-express.git"
    },
    "keywords": [
        "i18n",
        "express",
        "middleware",
        "json",
        "internationalisation",
        "node",
        "session",
        "language",
        "lang",
        "cookies",
        "javascript",
        "js",
        "handlebars",
        "ejs"
    ],
    "author": "koalazak <zak.tux@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/koalazak/i18n-express/issues"
    },
    "homepage": "https://github.com/koalazak/i18n-express"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
