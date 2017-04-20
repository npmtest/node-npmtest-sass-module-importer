# npmtest-sass-module-importer

#### basic test coverage for  sass-module-importer (v1.4.0)  [![npm package](https://img.shields.io/npm/v/npmtest-sass-module-importer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sass-module-importer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sass-module-importer.svg)](https://travis-ci.org/npmtest/node-npmtest-sass-module-importer)

#### Import Sass files from NPM and Bower Modules

[![NPM](https://nodei.co/npm/sass-module-importer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sass-module-importer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sass-module-importer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sass-module-importer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sass-module-importer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sass-module-importer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sass-module-importer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sass-module-importer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sass-module-importer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sass-module-importer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sass-module-importer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sass-module-importer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sass-module-importer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sass-module-importer/build/test-report.html](https://npmtest.github.io/node-npmtest-sass-module-importer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sass-module-importer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sass-module-importer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sass-module-importer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sass-module-importer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sass-module-importer",
    "version": "1.4.0",
    "main": "lib/index.js",
    "jsnext:main": "src/index.js",
    "description": "Import Sass files from NPM and Bower Modules",
    "author": "Lucas Motta <mail@lucasmotta.com> (lucasmotta.com)",
    "repository": {
        "type": "git",
        "url": "https://github.com/lucasmotta/sass-module-importer"
    },
    "bugs": {
        "url": "https://github.com/lucasmotta/sass-module-importer/issues"
    },
    "license": "MIT",
    "keywords": [
        "sass",
        "scss",
        "importer",
        "module",
        "npm",
        "node-sass",
        "bower"
    ],
    "scripts": {
        "build": "rollup -c",
        "lint": "eslint src/index.js test.js",
        "pretest": "npm run lint && npm run build",
        "test": "mocha --compilers js:buble/register",
        "prepublish": "npm test",
        "preversion": "npm test",
        "version": "npm run build",
        "postversion": "git push && git push --tags"
    },
    "devDependencies": {
        "buble": "^0.5.6",
        "chai": "^3.5.0",
        "eslint": "^2.8.0",
        "eslint-config-airbnb": "^6.1.0",
        "mocha": "^2.4.5",
        "node-sass": "^3.4.2",
        "rollup": "^0.25.4",
        "rollup-plugin-buble": "^0.5.0",
        "rollup-plugin-commonjs": "^3.1.0",
        "rollup-plugin-json": "^2.0.0",
        "rollup-plugin-node-resolve": "^1.5.0"
    },
    "dependencies": {
        "es6-map": "0.1.3",
        "glob": "^7.1.1",
        "object-assign": "4.0.1",
        "resolve": "1.1.7",
        "resolve-bower": "0.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
