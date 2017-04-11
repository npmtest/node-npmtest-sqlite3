# test coverage for  [sqlite3 (v3.1.8)](http://github.com/mapbox/node-sqlite3)  [![npm package](https://img.shields.io/npm/v/npmtest-sqlite3.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sqlite3) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sqlite3.svg)](https://travis-ci.org/npmtest/node-npmtest-sqlite3)
#### Asynchronous, non-blocking SQLite3 bindings

[![NPM](https://nodei.co/npm/sqlite3.png?downloads=true)](https://www.npmjs.com/package/sqlite3)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sqlite3/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sqlite3/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sqlite3/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sqlite3/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sqlite3/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sqlite3/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sqlite3/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sqlite3/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-sqlite3/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-sqlite3/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-sqlite3%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sqlite3/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sqlite3/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-sqlite3%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sqlite3/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sqlite3/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sqlite3/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "MapBox",
        "url": "https://mapbox.com/"
    },
    "binary": {
        "module_name": "node_sqlite3",
        "module_path": "./lib/binding/{node_abi}-{platform}-{arch}",
        "host": "https://mapbox-node-binary.s3.amazonaws.com",
        "remote_path": "./{name}/v{version}/{toolset}/",
        "package_name": "{node_abi}-{platform}-{arch}.tar.gz"
    },
    "bugs": {
        "url": "https://github.com/mapbox/node-sqlite3/issues"
    },
    "bundleDependencies": [
        "node-pre-gyp"
    ],
    "contributors": [
        {
            "name": "Konstantin Käfer",
            "email": "mail@kkaefer.com"
        },
        {
            "name": "Dane Springmeyer",
            "email": "dane@mapbox.com"
        },
        {
            "name": "Will White",
            "email": "will@mapbox.com"
        },
        {
            "name": "Orlando Vazquez",
            "email": "ovazquez@gmail.com"
        },
        {
            "name": "Artem Kustikov",
            "email": "kustikoff@gmail.com"
        },
        {
            "name": "Eric Fredricksen",
            "email": "efredricksen@gmail.com"
        },
        {
            "name": "John Wright",
            "email": "mrjjwright@gmail.com"
        },
        {
            "name": "Ryan Dahl",
            "email": "ry@tinyclouds.org"
        },
        {
            "name": "Tom MacWright",
            "email": "tom@mapbox.com"
        },
        {
            "name": "Carter Thaxton",
            "email": "carter.thaxton@gmail.com"
        },
        {
            "name": "Audrius Kažukauskas",
            "email": "audrius@neutrino.lt"
        },
        {
            "name": "Johannes Schauer",
            "email": "josch@pyneo.org"
        },
        {
            "name": "Nathan Rajlich",
            "email": "nathan@tootallnate.net"
        },
        {
            "name": "AJ ONeal",
            "email": "coolaj86@gmail.com"
        },
        {
            "name": "Mithgol"
        },
        {
            "name": "Ben Noordhuis",
            "email": "ben@strongloop.com"
        }
    ],
    "dependencies": {
        "nan": "~2.4.0",
        "node-pre-gyp": "~0.6.31"
    },
    "description": "Asynchronous, non-blocking SQLite3 bindings",
    "devDependencies": {
        "aws-sdk": "2.x",
        "eslint": "3.5.0",
        "mocha": "3.x"
    },
    "directories": {},
    "dist": {
        "shasum": "4cbcf965d8b901d1b1015cbc7fc415aae157dfaa",
        "tarball": "https://registry.npmjs.org/sqlite3/-/sqlite3-3.1.8.tgz"
    },
    "gitHead": "4800c6377ef15f467290d77776302b486e71ada3",
    "homepage": "http://github.com/mapbox/node-sqlite3",
    "keywords": [
        "sql",
        "sqlite",
        "sqlite3",
        "database"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/sqlite3",
    "maintainers": [
        {
            "name": "kkaefer",
            "email": "kkaefer@gmail.com"
        },
        {
            "name": "yhahn",
            "email": "young@developmentseed.org"
        },
        {
            "name": "tmcw",
            "email": "macwright@gmail.com"
        },
        {
            "name": "springmeyer",
            "email": "dane@dbsgeo.com"
        }
    ],
    "name": "sqlite3",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/mapbox/node-sqlite3.git"
    },
    "scripts": {
        "install": "node-pre-gyp install --fallback-to-build",
        "prepublish": "npm ls",
        "pretest": "node test/support/createdb.js",
        "test": "mocha -R spec --timeout 480000"
    },
    "version": "3.1.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
