# api documentation for  [tachyons (v4.7.0)](https://github.com/tachyons-css/tachyons#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-tachyons.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-tachyons) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-tachyons.svg)](https://travis-ci.org/npmdoc/node-npmdoc-tachyons)
#### Functional CSS for humans

[![NPM](https://nodei.co/npm/tachyons.png?downloads=true)](https://www.npmjs.com/package/tachyons)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tachyons/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-tachyons%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tachyons/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-tachyons/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-tachyons/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mrmrs"
    },
    "bugs": {
        "url": "https://github.com/tachyons-css/tachyons/issues"
    },
    "contributors": [
        {
            "name": "adam morse",
            "email": "hi@mrmrs.cc"
        },
        {
            "name": "john otander",
            "url": "http://johnotander.com"
        }
    ],
    "dependencies": {},
    "description": "Functional CSS for humans",
    "devDependencies": {
        "copy-files": "^0.1.0",
        "immutable-css-cli": "^1.1.1",
        "normalize.css": "^6.0.0",
        "tachyons-cli": "^1.0.10",
        "tachyons-modules": "^1.1.8",
        "watch": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "228eed0badca01cf793ef7cc6103a60c8f8b0f3e",
        "tarball": "https://registry.npmjs.org/tachyons/-/tachyons-4.7.0.tgz"
    },
    "files": [
        "css",
        "src"
    ],
    "gitHead": "2071e67133f802a7cbd636c59ffd550cfe8e6c8e",
    "homepage": "https://github.com/tachyons-css/tachyons#readme",
    "keywords": [
        "css",
        "oocss",
        "postcss",
        "functional css",
        "design",
        "responsive",
        "performance"
    ],
    "license": "MIT",
    "main": "css/tachyons.css",
    "maintainers": [
        {
            "name": "donnieberg",
            "email": "deeoverflow@gmail.com"
        },
        {
            "name": "johno",
            "email": "johnotander@gmail.com"
        },
        {
            "name": "mrmrs",
            "email": "hi@mrmrs.cc"
        }
    ],
    "name": "tachyons",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tachyons-css/tachyons.git"
    },
    "scripts": {
        "build": "npm run build:css && npm run build:minify",
        "build:css": "tachyons src/tachyons.css > css/tachyons.css",
        "build:minify": "tachyons src/tachyons.css -m > css/tachyons.min.css",
        "build:watch": "watch 'npm run build' ./src/",
        "mutations": "immutable-css src/tachyons.css --strict",
        "start": "npm run build:watch"
    },
    "style": "css/tachyons.min.css",
    "version": "4.7.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module tachyons](#apidoc.module.tachyons)



# <a name="apidoc.module.tachyons"></a>[module tachyons](#apidoc.module.tachyons)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
