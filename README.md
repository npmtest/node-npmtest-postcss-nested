# npmtest-postcss-nested

#### basic test coverage for  postcss-nested (v1.0.1)  [![npm package](https://img.shields.io/npm/v/npmtest-postcss-nested.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postcss-nested) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postcss-nested.svg)](https://travis-ci.org/npmtest/node-npmtest-postcss-nested)

#### PostCSS plugin to unwrap nested rules like how Sass does it.

[![NPM](https://nodei.co/npm/postcss-nested.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-nested)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postcss-nested/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-nested/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-nested/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postcss-nested/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-nested/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postcss-nested/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postcss-nested/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postcss-nested/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postcss-nested/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-nested/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postcss-nested/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postcss-nested/build/test-report.html](https://npmtest.github.io/node-npmtest-postcss-nested/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postcss-nested/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postcss-nested/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postcss-nested/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-nested/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-nested/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-nested/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postcss-nested/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postcss-nested/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "postcss-nested",
    "version": "1.0.1",
    "description": "PostCSS plugin to unwrap nested rules like how Sass does it.",
    "keywords": [
        "postcss",
        "css",
        "postcss-plugin",
        "sass",
        "nested"
    ],
    "author": "Andrey Sitnik <andrey@sitnik.ru>",
    "license": "MIT",
    "repository": "postcss/postcss-nested",
    "dependencies": {
        "postcss": "^5.2.17"
    },
    "devDependencies": {
        "eslint": "^3.12.2",
        "eslint-config-postcss": "^2.0.2",
        "jest": "^18.0.0"
    },
    "scripts": {
        "test": "jest && eslint *.js"
    },
    "eslintConfig": {
        "extends": "eslint-config-postcss/es5",
        "env": {
            "jest": true
        }
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
