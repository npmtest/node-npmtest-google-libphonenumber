# npmtest-google-libphonenumber

#### basic test coverage for  [google-libphonenumber (v2.0.15)](http://seegno.github.io/google-libphonenumber/)  [![npm package](https://img.shields.io/npm/v/npmtest-google-libphonenumber.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-google-libphonenumber) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-google-libphonenumber.svg)](https://travis-ci.org/npmtest/node-npmtest-google-libphonenumber)

#### The up-to-date and reliable Google's libphonenumber package for node.js.

[![NPM](https://nodei.co/npm/google-libphonenumber.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-libphonenumber)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-google-libphonenumber/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-google-libphonenumber/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-google-libphonenumber/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-google-libphonenumber/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-google-libphonenumber/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-google-libphonenumber/build/test-report.html](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-google-libphonenumber/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-libphonenumber/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-libphonenumber/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-libphonenumber/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-google-libphonenumber/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rui Marinho",
        "url": "http://seegno.com"
    },
    "bugs": {
        "url": "https://github.com/seegno/google-libphonenumber/issues"
    },
    "dependencies": {},
    "description": "The up-to-date and reliable Google's libphonenumber package for node.js.",
    "devDependencies": {
        "browserify": "^13.1.0",
        "eslint": "^3.5.0",
        "eslint-config-seegno": "^6.0.0",
        "mocha": "^3.0.2",
        "should": "^11.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d890959d2f7e374ff901296bc76d07f1e24adabe",
        "tarball": "https://registry.npmjs.org/google-libphonenumber/-/google-libphonenumber-2.0.15.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "7e88e7f5bcb031488e2438c48c722f1f70bec5d3",
    "homepage": "http://seegno.github.io/google-libphonenumber/",
    "keywords": [
        "browserify",
        "e164",
        "format",
        "formatting",
        "international",
        "libphonenumber",
        "number",
        "phone",
        "phonenumber",
        "rfc3966",
        "standardize",
        "wrapper"
    ],
    "license": "SEE LICENSE IN LICENSE",
    "main": "dist/libphonenumber.js",
    "maintainers": [
        {
            "name": "ruimarinho"
        }
    ],
    "name": "google-libphonenumber",
    "optionalDependencies": {},
    "options": {
        "mocha": "--require should test"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/seegno/google-libphonenumber.git"
    },
    "scripts": {
        "build": "bin/build.sh",
        "changelog": "github_changelog_generator --no-issues --header-label='# Changelog' --future-release=v$npm_config_future_release && sed -i '' -e :a -e '$d;N;2,3ba' -e 'P;D' CHANGELOG.md",
        "lint": "eslint src/index.js test",
        "prepublish": "npm run build",
        "test": "npm run build && npm run testonly",
        "testonly": "mocha $npm_package_options_mocha",
        "update": "bin/update.sh",
        "version": "npm run changelog --future-release=$npm_package_version && npm run build && git add -A CHANGELOG.md dist"
    },
    "version": "2.0.15",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
