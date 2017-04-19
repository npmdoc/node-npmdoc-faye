# npmdoc-faye

#### api documentation for  [faye (v1.2.4)](https://faye.jcoglan.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-faye.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-faye) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-faye.svg)](https://travis-ci.org/npmdoc/node-npmdoc-faye)

#### Simple pub/sub messaging for the web

[![NPM](https://nodei.co/npm/faye.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/faye)

- [https://npmdoc.github.io/node-npmdoc-faye/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-faye/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-faye/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-faye/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-faye/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-faye/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Coglan",
        "url": "http://jcoglan.com/"
    },
    "browser": "src/faye_browser",
    "bugs": {
        "url": "https://github.com/faye/faye/issues"
    },
    "dependencies": {
        "asap": "*",
        "csprng": "*",
        "faye-websocket": ">=0.9.1",
        "tough-cookie": "*",
        "tunnel-agent": "*"
    },
    "description": "Simple pub/sub messaging for the web",
    "devDependencies": {
        "imports-loader": "*",
        "jstest": "~1.0.0",
        "mime": "~1.2.0",
        "permessage-deflate": ">=0.1.0",
        "promises-aplus-tests": "~2.1.0",
        "uglifyjs": "*",
        "webpack": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "978ed8a58f1d481e5c1f98bacb8959de5ec5c643",
        "tarball": "https://registry.npmjs.org/faye/-/faye-1.2.4.tgz"
    },
    "engines": {
        "node": ">=0.6.0"
    },
    "homepage": "https://faye.jcoglan.com",
    "keywords": [
        "comet",
        "websocket",
        "pubsub",
        "bayeux",
        "ajax",
        "http"
    ],
    "license": "MIT",
    "main": "src/faye_node",
    "maintainers": [
        {
            "name": "jcoglan"
        }
    ],
    "name": "faye",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/faye/faye.git"
    },
    "scripts": {
        "promise": "promises-aplus-tests src/util/promise.js",
        "test": "find spec -name '*_spec.js' | xargs jstest"
    },
    "version": "1.2.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
