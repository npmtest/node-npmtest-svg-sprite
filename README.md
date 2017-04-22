# npmtest-svg-sprite

#### basic test coverage for  [svg-sprite (v1.3.6)](https://github.com/jkphl/svg-sprite)  [![npm package](https://img.shields.io/npm/v/npmtest-svg-sprite.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-svg-sprite) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-svg-sprite.svg)](https://travis-ci.org/npmtest/node-npmtest-svg-sprite)

#### SVG sprites & stacks galore — A low-level Node.js module that takes a bunch of SVG files, optimizes them and bakes them into SVG sprites of several types along with suitable stylesheet resources (e.g. CSS, Sass, LESS, Stylus, etc.)

[![NPM](https://nodei.co/npm/svg-sprite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg-sprite)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-svg-sprite/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg-sprite/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-svg-sprite/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-svg-sprite/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-svg-sprite/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-svg-sprite/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-svg-sprite/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-svg-sprite/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-svg-sprite/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-svg-sprite/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-svg-sprite/build/test-report.html](https://npmtest.github.io/node-npmtest-svg-sprite/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-svg-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-svg-sprite/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-svg-sprite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg-sprite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg-sprite/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-svg-sprite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-svg-sprite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joschi Kuphal",
        "url": "https://jkphl.is"
    },
    "bin": {
        "svg-sprite": "./bin/svg-sprite.js"
    },
    "bugs": {
        "url": "https://github.com/jkphl/svg-sprite/issues"
    },
    "dependencies": {
        "async": "^2.0.1",
        "css-selector-parser": "^1.1.0",
        "cssmin": "^0.4.3",
        "cssom": "^0.3.1",
        "glob": "^7.0.6",
        "js-yaml": "^3.6.1",
        "lodash": "^4.15.0",
        "lodash.pluck": "^3.1.2",
        "mkdirp": "^0.5.1",
        "mustache": "^2.2.1",
        "phantomjs-prebuilt": "^2.1.12",
        "prettysize": "^0.0.3",
        "svgo": "0.7.0",
        "vinyl": "^1.2.0",
        "winston": "^2.2.0",
        "xmldom": "0.1.22",
        "xpath": "^0.0.23",
        "yargs": "^5.0.0"
    },
    "description": "SVG sprites & stacks galore — A low-level Node.js module that takes a bunch of SVG files, optimizes them and bakes them into SVG sprites of several types along with suitable stylesheet resources (e.g. CSS, Sass, LESS, Stylus, etc.)",
    "devDependencies": {
        "coveralls": "*",
        "image-diff": "^1.6.3",
        "istanbul": "*",
        "jshint": "^2.9.3",
        "less": "^2.7.1",
        "mocha": "",
        "mocha-lcov-reporter": "*",
        "node-sass": "^3.8.0",
        "pn": "^1.0.0",
        "rimraf": "",
        "should": "",
        "stylus": "^0.54.5",
        "svg2png": "github:jkphl/svg2png",
        "vinyl-fs": "^2.4.3"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "7933de073ff6671d2b13f2461e64df730eb8ab34",
        "tarball": "https://registry.npmjs.org/svg-sprite/-/svg-sprite-1.3.6.tgz"
    },
    "engines": {
        "node": ">= 4.0"
    },
    "files": [
        "bin",
        "docs",
        "lib",
        "tmpl",
        "CHANGELOG.md"
    ],
    "gitHead": "46b54b1c384bc296efc34d691d27db233d443641",
    "homepage": "https://github.com/jkphl/svg-sprite",
    "keywords": [
        "icon",
        "icons",
        "svg",
        "png",
        "sprite",
        "spritesheet",
        "stack",
        "generator",
        "css",
        "sass",
        "less",
        "stylus",
        "stylesheet",
        "inline",
        "html",
        "vector",
        "rwd",
        "retina",
        "mustache",
        "gulpfriendly"
    ],
    "license": "MIT",
    "main": "lib/svg-sprite.js",
    "maintainers": [
        {
            "name": "jkphl"
        }
    ],
    "name": "svg-sprite",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jkphl/svg-sprite.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "lint": "jshint bin && jshint lib && jshint test",
        "test": "istanbul test _mocha --report html -- test/*.js --reporter spec"
    },
    "version": "1.3.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
