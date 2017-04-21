# npmtest-cordova-fabric-plugin

#### basic test coverage for  cordova-fabric-plugin (v1.1.7)  [![npm package](https://img.shields.io/npm/v/npmtest-cordova-fabric-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cordova-fabric-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cordova-fabric-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-cordova-fabric-plugin)

#### Cordova Fabric.io Plugin

[![NPM](https://nodei.co/npm/cordova-fabric-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cordova-fabric-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cordova-fabric-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cordova-fabric-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cordova-fabric-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cordova-fabric-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova-fabric-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova-fabric-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cordova-fabric-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cordova-fabric-plugin",
    "version": "1.1.7",
    "description": "Cordova Fabric.io Plugin",
    "cordova": {
        "id": "cordova-fabric-plugin",
        "platforms": [
            "android",
            "ios"
        ]
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/sarriaroman/FabricPlugin"
    },
    "keywords": [
        "cordova",
        "fabric",
        "crashlytics",
        "answers",
        "events",
        "device",
        "ecosystem:cordova",
        "cordova-android",
        "cordova-ios"
    ],
    "author": "Roman A. Sarria",
    "contributors": [
        {
            "name": "Justin Unterreiner",
            "url": "https://github.com/Justin-Credible"
        }
    ],
    "license": "MIT",
    "scripts": {
        "transpile": "node_modules/.bin/babel www/*.es6 --out-dir ."
    },
    "devDependencies": {
        "babel": "^5.8.35"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
