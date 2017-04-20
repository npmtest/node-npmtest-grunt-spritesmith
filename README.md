# npmtest-grunt-spritesmith

#### basic test coverage for  [grunt-spritesmith (v6.4.0)](https://github.com/Ensighten/grunt-spritesmith)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-spritesmith.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-spritesmith) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-spritesmith.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-spritesmith)

#### Grunt task for converting a set of images into a spritesheet and corresponding CSS variables.

[![NPM](https://nodei.co/npm/grunt-spritesmith.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-spritesmith)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-spritesmith/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-spritesmith/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-spritesmith/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-spritesmith/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-spritesmith/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-spritesmith/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-spritesmith/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-spritesmith/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-spritesmith",
    "description": "Grunt task for converting a set of images into a spritesheet and corresponding CSS variables.",
    "version": "6.4.0",
    "homepage": "https://github.com/Ensighten/grunt-spritesmith",
    "author": {
        "name": "Todd Wolfson",
        "url": "http://twolfson.com/"
    },
    "contributors": [
        {
            "name": "dpolivy"
        },
        {
            "name": "pdehaan",
            "url": "http://about.me/peterdehaan"
        },
        {
            "name": "MoOx",
            "url": "http://moox.io/"
        },
        {
            "name": "jasonsandmeyer",
            "url": "http://jasonsandmeyer.com"
        },
        {
            "name": "scanieso"
        },
        {
            "name": "STuFF"
        }
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/Ensighten/grunt-spritesmith.git"
    },
    "bugs": {
        "url": "https://github.com/Ensighten/grunt-spritesmith/issues"
    },
    "license": "MIT",
    "main": "tasks/grunt-spritesmith.js",
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "precheck": "twolfson-style precheck docs/ src/ src-test/ tasks/",
        "lint": "twolfson-style lint docs/ src/ src-test/ tasks/",
        "pretest": "twolfson-style install",
        "test": "npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint"
    },
    "dependencies": {
        "async": "~1.5.0",
        "spritesheet-templates": "~10.2.0",
        "spritesmith": "~3.1.0",
        "underscore": "~1.4.2",
        "url2": "1.0.0"
    },
    "devDependencies": {
        "foundry": "~4.3.2",
        "foundry-release-git": "~2.0.2",
        "foundry-release-npm": "~2.0.2",
        "get-pixels": "~3.2.3",
        "gmsmith": "~1.0.0",
        "grunt": "~0.4.2",
        "grunt-cli": "~0.1.13",
        "grunt-newer": "~0.8.0",
        "js-yaml": "~3.2.3",
        "jscs": "~1.8.1",
        "jshint": "~2.5.10",
        "mocha": "~1.21.5",
        "rimraf": "~2.2.8",
        "shell-quote": "~1.4.2",
        "twolfson-style": "~1.6.0"
    },
    "keywords": [
        "grunt",
        "gruntplugin",
        "sprite",
        "image",
        "spritesheet",
        "css",
        "spritesmith",
        "cross-platform"
    ],
    "foundry": {
        "releaseCommands": [
            "foundry-release-git",
            "foundry-release-npm"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
