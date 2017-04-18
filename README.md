# npmtest-pg

#### test coverage for  [pg (v6.1.5)](http://github.com/brianc/node-postgres)  [![npm package](https://img.shields.io/npm/v/npmtest-pg.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pg) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pg.svg)](https://travis-ci.org/npmtest/node-npmtest-pg)

#### PostgreSQL client - pure javascript & libpq with the same API

[![NPM](https://nodei.co/npm/pg.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pg)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pg/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pg/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pg/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pg/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pg/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pg/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pg/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pg/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pg/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pg/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pg/build/test-report.html](https://npmtest.github.io/node-npmtest-pg/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pg/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pg/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pg/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pg/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pg/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pg/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian Carlson"
    },
    "bugs": {
        "url": "https://github.com/brianc/node-postgres/issues"
    },
    "dependencies": {
        "buffer-writer": "1.0.1",
        "packet-reader": "0.2.0",
        "pg-connection-string": "0.1.3",
        "pg-pool": "1.*",
        "pg-types": "1.*",
        "pgpass": "1.x",
        "semver": "4.3.2"
    },
    "description": "PostgreSQL client - pure javascript & libpq with the same API",
    "devDependencies": {
        "async": "0.9.0",
        "co": "4.6.0",
        "jshint": "2.5.2",
        "lodash": "4.13.1",
        "pg-copy-streams": "0.3.0",
        "promise-polyfill": "5.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "204fa40c1252ab7220d7cf6992886b20d77862b8",
        "tarball": "https://registry.npmjs.org/pg/-/pg-6.1.5.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "3de22ba991676534b366144c02145c015cca6125",
    "homepage": "http://github.com/brianc/node-postgres",
    "keywords": [
        "postgres",
        "pg",
        "libpq",
        "postgre",
        "database",
        "rdbms"
    ],
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "brianc"
        }
    ],
    "minNativeVersion": "1.7.0",
    "name": "pg",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/brianc/node-postgres.git"
    },
    "scripts": {
        "changelog": "npm i github-changes && ./node_modules/.bin/github-changes -o brianc -r node-postgres -d pulls -a -v",
        "test": "make test-all connectionString=postgres://postgres@localhost:5432/postgres"
    },
    "version": "6.1.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
