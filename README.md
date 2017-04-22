# npmdoc-crawler

#### api documentation for  [crawler (v1.0.4)](https://github.com/bda-research/node-crawler)  [![npm package](https://img.shields.io/npm/v/npmdoc-crawler.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-crawler) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-crawler.svg)](https://travis-ci.org/npmdoc/node-npmdoc-crawler)

#### Crawler is a web spider written with Nodejs. It gives you the full power of jQuery on the server to parse a big number of pages as they are downloaded, asynchronously

[![NPM](https://nodei.co/npm/crawler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/crawler)

- [https://npmdoc.github.io/node-npmdoc-crawler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-crawler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-crawler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-crawler/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-crawler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-crawler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/bda-research/node-crawler/issues"
    },
    "dependencies": {
        "bottleneckp": "~1.1.0",
        "charset-parser": "^0.2.0",
        "cheerio": "^0.22.0",
        "iconv-lite": "^0.4.8",
        "lodash": "^4.17.4",
        "request": "~2.79.0",
        "seenreq": "^0.1.7",
        "type-is": "^1.6.14"
    },
    "description": "Crawler is a web spider written with Nodejs. It gives you the full power of jQuery on the server to parse a big number of pages as they are downloaded, asynchronously",
    "devDependencies": {
        "chai": "^2.3.0",
        "jsdom": "^9.6.0",
        "mocha": "^2.2.5",
        "mocha-testdata": "^1.1.0",
        "sinon": "^1.14.1",
        "whacko": "^0.19.1"
    },
    "directories": {
        "test": "tests"
    },
    "dist": {
        "shasum": "6beb7106bde85817586575ef181be07c1c21efb3",
        "tarball": "https://registry.npmjs.org/crawler/-/crawler-1.0.4.tgz"
    },
    "engine-strict": {
        "node": ">=4.0.0"
    },
    "gitHead": "16e372b3aea52ab06ef21a39255067939a03a76b",
    "homepage": "https://github.com/bda-research/node-crawler",
    "keywords": [
        "dom",
        "javascript",
        "crawling",
        "spider",
        "scraper",
        "scraping",
        "jquery",
        "crawler",
        "nodejs"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/bda-research/node-crawler/blob/master/LICENSE.txt"
        }
    ],
    "main": "./lib/crawler.js",
    "maintainers": [
        {
            "name": "darrenqc"
        },
        {
            "name": "mike442144"
        },
        {
            "name": "paulvalla"
        },
        {
            "name": "sylvinus"
        }
    ],
    "name": "crawler",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bda-research/node-crawler.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js"
    },
    "version": "1.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
