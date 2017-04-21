# npmdoc-reveal-md

#### api documentation for  reveal-md (v0.1.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-reveal-md.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-reveal-md) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-reveal-md.svg)](https://travis-ci.org/npmdoc/node-npmdoc-reveal-md)

#### reveal.js on steroids! Get beautiful reveal.js presentations from your Markdown files.

[![NPM](https://nodei.co/npm/reveal-md.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/reveal-md)

- [https://npmdoc.github.io/node-npmdoc-reveal-md/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-reveal-md/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-reveal-md/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-reveal-md/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-reveal-md/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-reveal-md/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "reveal-md",
    "description": "reveal.js on steroids! Get beautiful reveal.js presentations from your Markdown files.",
    "keywords": [
        "markdown",
        "reveal",
        "revealjs",
        "html",
        "server",
        "cli"
    ],
    "version": "0.1.3",
    "repository": {
        "type": "git",
        "url": "git://github.com/webpro/reveal-md.git"
    },
    "license": "MIT",
    "bin": {
        "reveal-md": "bin/cli.js"
    },
    "scripts": {
        "test": "mocha",
        "lint": "eslint bin lib",
        "fix": "eslint bin lib --fix"
    },
    "dependencies": {
        "bluebird": "^3.4.7",
        "commander": "2.9.0",
        "express": "4.14.1",
        "fs-extra": "^2.0.0",
        "glob": "7.1.1",
        "got": "^6.7.1",
        "highlight.js": "9.9.0",
        "livereload": "^0.6.0",
        "lodash": "^4.17.4",
        "mustache": "2.3.0",
        "open": "0.0.5",
        "reveal.js": "3.4.1",
        "yaml-front-matter": "^3.4.0"
    },
    "devDependencies": {
        "debug": "^2.6.1",
        "eslint": "^3.15.0",
        "eslint-plugin-import": "^2.2.0",
        "expect": "^1.20.2",
        "mocha": "^3.2.0"
    },
    "engines": {
        "node": ">=4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
