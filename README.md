# npmdoc-pm2

#### api documentation for  [pm2 (v2.4.5)](http://pm2.keymetrics.io/)  [![npm package](https://img.shields.io/npm/v/npmdoc-pm2.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pm2) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pm2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pm2)

#### Production process manager for Node.JS applications with a built-in load balancer.

[![NPM](https://nodei.co/npm/pm2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pm2)

- [https://npmdoc.github.io/node-npmdoc-pm2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pm2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pm2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pm2/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pm2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pm2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Strzelewicz Alexandre",
        "url": "https://keymetrics.io"
    },
    "bin": {
        "pm2": "./bin/pm2",
        "rundev": "./bin/rundev",
        "pm2-dev": "./bin/pm2-dev",
        "pm2-docker": "./bin/pm2-docker"
    },
    "bugs": {
        "url": "https://github.com/Unitech/pm2/issues"
    },
    "contributors": [
        {
            "name": "Alex Kocharin"
        },
        {
            "name": "Soyuka"
        },
        {
            "name": "Joni Shkurti"
        },
        {
            "name": "James Ide"
        },
        {
            "name": "Jun Tjatse"
        },
        {
            "name": "Xu Jingxin"
        },
        {
            "name": "Ben Postlethwaite"
        },
        {
            "name": "Devo.ps"
        },
        {
            "name": "Bret Copeland"
        },
        {
            "name": "John Hurliman"
        },
        {
            "name": "TruongSinh Tran-Nguyen"
        },
        {
            "name": "Michael Hueuberger"
        },
        {}
    ],
    "dependencies": {
        "async": "1.5",
        "blessed": "^0.1.81",
        "chalk": "^1.1",
        "chokidar": "^1.6.1",
        "cli-table": "0.3.1",
        "commander": "^2.9",
        "cron": "1.2.1",
        "debug": "^2.3.2",
        "eventemitter2": "1.0.5",
        "fclone": "1.0.11",
        "mkdirp": "0.5.1",
        "moment": "^2.15",
        "nssocket": "0.6.0",
        "pidusage": "^1.1.0",
        "pm2-axon": "3.0.2",
        "pm2-axon-rpc": "0.4.5",
        "pm2-deploy": "^0.3.5",
        "pm2-multimeter": "^0.1.2",
        "pmx": "^1.1.0",
        "semver": "^5.2",
        "shelljs": "0.7.7",
        "source-map-support": "^0.4.6",
        "sprintf-js": "~1.0.2",
        "vizion": "^0.2",
        "yamljs": "0.2.8"
    },
    "description": "Production process manager for Node.JS applications with a built-in load balancer.",
    "devDependencies": {
        "mocha": "^3",
        "should": "^11"
    },
    "directories": {
        "bin": "./bin",
        "lib": "./lib",
        "example": "./examples"
    },
    "dist": {
        "shasum": "14c7722eb854f7f409b2ebef83f03470ecd03fc9",
        "tarball": "https://registry.npmjs.org/pm2/-/pm2-2.4.5.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "e18d976788255ff985d29c62c8614005e17c3103",
    "homepage": "http://pm2.keymetrics.io/",
    "keywords": [
        "cli",
        "fault tolerant",
        "sysadmin",
        "tools",
        "pm2",
        "logs",
        "log",
        "json",
        "express",
        "hapi",
        "kraken",
        "reload",
        "microservice",
        "programmatic",
        "harmony",
        "node-pm2",
        "production",
        "keymetrics",
        "node.js monitoring",
        "strong-pm",
        "deploy",
        "deployment",
        "daemon",
        "supervisor",
        "nodemon",
        "pm2.io",
        "ghost",
        "ghost production",
        "monitoring",
        "process manager",
        "forever",
        "profiling",
        "probes",
        "forever-monitor",
        "keep process alive",
        "process configuration",
        "clustering",
        "cluster cli",
        "cluster",
        "cron",
        "devops",
        "dev ops"
    ],
    "license": "AGPL-3.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "tknew"
        }
    ],
    "name": "pm2",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/Unitech/pm2.git"
    },
    "scripts": {
        "bench-pmx": "pm2 delete all; pm2 install pm2-probe; node examples/pmx/app.js; pm2 ls",
        "test": "NODE_ENV=test bash test/pm2_programmatic_tests.sh && NODE_ENV=test bash test/pm2_behavior_tests.sh"
    },
    "version": "2.4.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
