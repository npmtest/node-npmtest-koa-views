# npmtest-koa-views

#### basic test coverage for  koa-views (v6.0.2)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-views.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-views) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-views.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-views)

#### Template rendering middleware for koa

[![NPM](https://nodei.co/npm/koa-views.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-views)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-views/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-views/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-views/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-views/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-views/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-koa-views/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-koa-views/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-views/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-views/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-views/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-views/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-views/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-views/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-views/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-views/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-views/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-views/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-views/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-views/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-views/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-views/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-views/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-views/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "koa-views",
    "version": "6.0.2",
    "description": "Template rendering middleware for koa",
    "main": "src/index.js",
    "scripts": {
        "lint": "eslint .",
        "xyz": "xyz",
        "test": "mocha --reporter dot --bail"
    },
    "precommit": "lint, test",
    "dependencies": {
        "consolidate": "^0.14.1",
        "debug": "^2.1.3",
        "koa-send": "^4.0.0",
        "mz": "^2.4.0"
    },
    "devDependencies": {
        "ejs": "^2.4.1",
        "eslint": "^2.2.0",
        "eslint-config-standard": "^5.1.0",
        "eslint-plugin-promise": "^1.0.8",
        "eslint-plugin-standard": "^1.3.2",
        "handlebars": "^4.0.5",
        "koa": "^2.0.0-alpha.3",
        "mocha": "^2.2.4",
        "nunjucks": "^3.0.0",
        "pre-commit": "^1.2.2",
        "pug": "^0.1.0",
        "should": "^7.0.2",
        "supertest": "^1.0.1",
        "tap-spec": "^4.1.1",
        "tape": "^4.4.0",
        "underscore": "^1.8.3",
        "xyz": "^0.5.0"
    },
    "peerDependencies": {
        "koa": "2.x"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/queckezz/koa-views"
    },
    "keywords": [
        "koa",
        "render",
        "views",
        "app-wide",
        "templating",
        "templates"
    ],
    "author": "queckezz",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/queckezz/koa-views/issues"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
