# npmtest-npm-collection-staff-picks

#### basic test coverage for  [npm-collection-staff-picks (v1.0.2)](https://github.com/npm/npm-collection-staff-picks)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-collection-staff-picks.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-collection-staff-picks) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-collection-staff-picks.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-collection-staff-picks)

#### A list of obscure and beloved npm packages, selected by the staff at npm

[![NPM](https://nodei.co/npm/npm-collection-staff-picks.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-collection-staff-picks)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-collection-staff-picks/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-collection-staff-picks/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-collection-staff-picks/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "npm-collection-staff-picks",
    "version": "1.0.2",
    "description": "A list of obscure and beloved npm packages, selected by the staff at npm",
    "main": "meta.json",
    "scripts": {
        "prepublish": "npm run meta",
        "meta": "node lib/meta.js",
        "postinstall": "backfill"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/npm/npm-collection-staff-picks"
    },
    "keywords": [
        "npm",
        "collection",
        "faves"
    ],
    "author": "zeke",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/npm/npm-collection-staff-picks/issues"
    },
    "homepage": "https://github.com/npm/npm-collection-staff-picks",
    "dependencies": {
        "backoff": "^2.4.0",
        "bistre": "^1.0.0",
        "blade": "^3.3.0",
        "bole": "^1.0.0",
        "cheerio": "^0.18.0",
        "dashdash": "^1.7.0",
        "inquirer": "^0.8.0",
        "json": "^9.0.2",
        "must": "^0.12.0",
        "nearley": "^1.0.1",
        "p-promise": "^0.4.8",
        "package-json-to-readme": "^1.0.1",
        "replify": "^1.2.0",
        "replpad": "^0.12.0",
        "shimmer": "^1.0.0",
        "sprintf-js": "^1.0.2",
        "stackup": "0.0.5",
        "standard-error": "^1.1.0",
        "superagent": "^0.20.0",
        "zeroclipboard": "^2.1.6"
    },
    "devDependencies": {
        "backfill": "^1.0.1",
        "find-root": "^0.1.1",
        "pkgs": "^1.2.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
