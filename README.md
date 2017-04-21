# npmdoc-wemo-client

#### api documentation for  [wemo-client (v0.11.2)](https://github.com/timonreinhard/wemo-client)  [![npm package](https://img.shields.io/npm/v/npmdoc-wemo-client.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-wemo-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-wemo-client.svg)](https://travis-ci.org/npmdoc/node-npmdoc-wemo-client)

#### Client library for interacting with Belkin Wemo devices

[![NPM](https://nodei.co/npm/wemo-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wemo-client)

- [https://npmdoc.github.io/node-npmdoc-wemo-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wemo-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wemo-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wemo-client/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-wemo-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-wemo-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "wemo-client",
    "version": "0.11.2",
    "description": "Client library for interacting with Belkin Wemo devices",
    "main": "index.js",
    "directories": {
        "examples": "./examples"
    },
    "scripts": {
        "test": "istanbul test _mocha",
        "test-cov": "istanbul cover _mocha",
        "test-e2e": "mocha ./test-e2e",
        "lint": "eslint *.js",
        "prepush": "npm run lint && npm test",
        "postmerge": "npm install",
        "preversion": "npm test",
        "postversion": "git push && git push --tags"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/timonreinhard/wemo-client.git"
    },
    "author": "Timon Reinhard",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/timonreinhard/wemo-client/issues"
    },
    "homepage": "https://github.com/timonreinhard/wemo-client",
    "keywords": [
        "wemo"
    ],
    "dependencies": {
        "debug": "~2.2.0",
        "entities": "^1.1.1",
        "node-ssdp": "~2.8.0",
        "xml2js": "~0.4.16",
        "xmlbuilder": "^8.2.2"
    },
    "devDependencies": {
        "codeclimate-test-reporter": "^0.1.1",
        "eslint": "^3.2.2",
        "husky": "^0.10.2",
        "istanbul": "^0.4.4",
        "mitm": "^1.3.0",
        "mocha": "^3.0.2",
        "must": "^0.13.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
