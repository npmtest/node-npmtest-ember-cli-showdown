# npmtest-ember-cli-showdown

#### basic test coverage for  [ember-cli-showdown (v3.0.0)](https://github.com/gcollazo/ember-cli-showdown)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli-showdown.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli-showdown) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli-showdown.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli-showdown)

#### Ember component to render markdown into HTML.

[![NPM](https://nodei.co/npm/ember-cli-showdown.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli-showdown)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli-showdown/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ember-cli-showdown/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli-showdown/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli-showdown/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli-showdown/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli-showdown/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-showdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-showdown/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli-showdown/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bugs": {
        "url": "https://github.com/gcollazo/ember-cli-showdown/issues"
    },
    "dependencies": {
        "broccoli-funnel": "^1.0.1",
        "broccoli-merge-trees": "^1.1.1",
        "ember-cli-babel": "^5.1.3",
        "ember-cli-htmlbars": "^1.0.8",
        "ember-cli-htmlbars-inline-precompile": "^0.3.2",
        "ember-cli-import-polyfill": "^0.2.0",
        "ember-getowner-polyfill": "^1.2.2",
        "showdown": "^1.6.4"
    },
    "description": "Ember component to render markdown into HTML.",
    "devDependencies": {
        "broccoli-asset-rev": "^2.1.2",
        "ember-cli": "1.13.8",
        "ember-cli-app-version": "0.5.0",
        "ember-cli-content-security-policy": "0.4.0",
        "ember-cli-dependency-checker": "^1.0.1",
        "ember-cli-inject-live-reload": "^1.3.1",
        "ember-cli-qunit": "^1.0.0",
        "ember-cli-release": "0.2.3",
        "ember-cli-sri": "^1.0.3",
        "ember-cli-uglify": "^1.2.0",
        "ember-disable-prototype-extensions": "^1.0.0",
        "ember-disable-proxy-controllers": "^1.0.0",
        "ember-export-application-global": "^1.0.3",
        "ember-try": "0.0.6"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "0295744aa316259f7c95ad66522696636de31979",
        "tarball": "https://registry.npmjs.org/ember-cli-showdown/-/ember-cli-showdown-3.0.0.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "demoURL": "https://gcollazo.github.io/ember-cli-showdown/",
        "fastbootDependencies": [
            "showdown"
        ]
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "gitHead": "6fb944be49f0d0c9f8c1715920bc7eae60809ed5",
    "homepage": "https://github.com/gcollazo/ember-cli-showdown",
    "keywords": [
        "ember-addon",
        "showdown",
        "markdown",
        "component",
        "emberjs"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "gcollazo"
        },
        {
            "name": "jasonmit"
        },
        {
            "name": "jpadilla"
        }
    ],
    "name": "ember-cli-showdown",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/gcollazo/ember-cli-showdown.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:testall"
    },
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
