# npmdoc-cache-manager-redis

#### api documentation for  cache-manager-redis (v0.4.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-cache-manager-redis.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cache-manager-redis) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cache-manager-redis.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cache-manager-redis)

#### Redis store for the node-cache-manager

[![NPM](https://nodei.co/npm/cache-manager-redis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cache-manager-redis)

- [https://npmdoc.github.io/node-npmdoc-cache-manager-redis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cache-manager-redis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cache-manager-redis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cache-manager-redis/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cache-manager-redis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cache-manager-redis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cache-manager-redis",
    "version": "0.4.0",
    "description": "Redis store for the node-cache-manager",
    "main": "index.js",
    "scripts": {
        "test": "node_modules/.bin/mocha --recursive test",
        "coverage": "node_modules/.bin/istanbul cover _mocha -- test --recursive",
        "lint": "node_modules/.bin/jshint .",
        "jsdoc": "node_modules/.bin/jsdoc . --package package.json --readme README.md --template node_modules/minami --destination docs"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/dial-once/node-cache-manager-redis.git"
    },
    "keywords": [
        "cache",
        "redis",
        "cache manager",
        "multiple cache"
    ],
    "author": "Dial Once",
    "license": "MIT",
    "dependencies": {
        "cache-manager": "^2.2.0",
        "redis-url": "^1.2.1",
        "sol-redis-pool": "^0.3.2"
    },
    "devDependencies": {
        "istanbul": "^0.4.0",
        "jsdoc": "^3.3.3",
        "jshint": "^2.8.0",
        "minami": "^1.1.1",
        "mocha": "^3.0.2",
        "sinon": "^1.17.2"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
