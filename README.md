# npmtest-intl

#### basic test coverage for  [intl (v1.2.5)](https://github.com/andyearnshaw/Intl.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-intl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-intl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-intl.svg)](https://travis-ci.org/npmtest/node-npmtest-intl)

#### Polyfill the ECMA-402 Intl API (except collation)

[![NPM](https://nodei.co/npm/intl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/intl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-intl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-intl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-intl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-intl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-intl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-intl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-intl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-intl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-intl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-intl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-intl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-intl/build/test-report.html](https://npmtest.github.io/node-npmtest-intl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-intl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-intl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-intl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-intl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-intl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-intl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-intl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-intl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andy Earnshaw"
    },
    "browser": {
        "./locale-data/complete": false,
        "./locale-data/complete.js": false
    },
    "bugs": {
        "url": "https://github.com/andyearnshaw/Intl.js/issues"
    },
    "dependencies": {},
    "description": "Polyfill the ECMA-402 Intl API (except collation)",
    "devDependencies": {
        "async": "^0.9.0",
        "babel-cli": "^6.2.0",
        "babel-eslint": "^6.1.2",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.4.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.3.13",
        "babel-plugin-transform-es3-property-literals": "^6.3.13",
        "babel-plugin-transform-object-rest-spread": "^6.1.18",
        "babel-polyfill": "^6.3.14",
        "babel-preset-es2015": "6.1.18",
        "babel-preset-es2015-rollup": "1.1.1",
        "babel-register": "^6.2.0",
        "cldr-cal-buddhist-full": "28.0.0",
        "cldr-cal-chinese-full": "28.0.0",
        "cldr-cal-coptic-full": "28.0.0",
        "cldr-cal-dangi-full": "28.0.0",
        "cldr-cal-ethiopic-full": "28.0.0",
        "cldr-cal-hebrew-full": "28.0.0",
        "cldr-cal-indian-full": "28.0.0",
        "cldr-cal-islamic-full": "28.0.0",
        "cldr-cal-japanese-full": "28.0.0",
        "cldr-cal-persian-full": "28.0.0",
        "cldr-cal-roc-full": "28.0.0",
        "cldr-core": "28.0.0",
        "cldr-dates-full": "28.0.0",
        "cldr-numbers-full": "28.0.0",
        "cli-color": "^1.0.0",
        "clui": "^0.3.1",
        "eslint": "^2.2.0",
        "estraverse-fb": "^1.3.1",
        "finalhandler": "^0.4.0",
        "glob": "^5.0.3",
        "grunt": "^0.4.5",
        "grunt-cli": "~0.1.13",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-copy": "^0.5.0",
        "grunt-curl": "^2.1.0",
        "grunt-zip": "^0.16.2",
        "jshint": "^2.5.5",
        "mkdirp": "^0.5.1",
        "object.assign": "^1.1.1",
        "rimraf": "^2.4.2",
        "rollup": "^0.26.0",
        "rollup-plugin-babel": "^2.3.9",
        "rollup-plugin-commonjs": "^2.2.0",
        "rollup-plugin-memory": "^1.0.0",
        "rollup-plugin-npm": "^1.3.0",
        "rollup-plugin-replace": "^1.1.0",
        "rollup-plugin-uglify": "^0.1.0",
        "sauce-tunnel": "^2.2.3",
        "serve-static": "^1.10.0",
        "wd": "^0.3.6"
    },
    "directories": {
        "test": "tests"
    },
    "dist": {
        "shasum": "82244a2190c4e419f8371f5aa34daa3420e2abde",
        "tarball": "https://registry.npmjs.org/intl/-/intl-1.2.5.tgz"
    },
    "email": "andyearnshaw@gmail.com",
    "gitHead": "9ad9a125ecf6ee695e23f8f976e98d3be3733aec",
    "homepage": "https://github.com/andyearnshaw/Intl.js#readme",
    "keywords": [
        "intl",
        "i18n",
        "internationalization",
        "ecma402",
        "polyfill"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "andyearnshaw"
        },
        {
            "name": "caridy"
        }
    ],
    "name": "intl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andyearnshaw/Intl.js.git"
    },
    "scripts": {
        "build": "npm run build:data && npm run build:lib && npm run build:dist",
        "build:data": "babel-node scripts/build-data",
        "build:dist": "npm run build:dist:dev && npm run build:dist:prod",
        "build:dist:dev": "NODE_ENV=development babel-node scripts/build-dist",
        "build:dist:prod": "NODE_ENV=production babel-node scripts/build-dist",
        "build:lib": "babel-node scripts/build-lib",
        "clean": "rimraf dist/ lib/ locale-data/",
        "lint": "eslint .",
        "prepublish": "npm run clean && npm run build",
        "pretest": "npm run lint",
        "preversion": "npm run clean && npm run build && npm run test",
        "test": "cd tests && node polyfilling.js && node sanity.js && node disableregexprestore.js && node noderunner.js && node saucelabs.js"
    },
    "version": "1.2.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
