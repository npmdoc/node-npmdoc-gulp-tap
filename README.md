# npmdoc-gulp-tap

#### basic api documentation for  [gulp-tap (v0.4.2)](https://github.com/geejs/gulp-tap)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-tap.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-tap) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-tap.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-tap)

#### Easiest way to tap into a pipeline

[![NPM](https://nodei.co/npm/gulp-tap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-tap)

- [https://npmdoc.github.io/node-npmdoc-gulp-tap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-tap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-tap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-tap/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-tap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-tap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Mario Gutierrez <mario@mgutz.com>",
        "Jon Ege Ronnenberg <jon.ronnenberg@gmail.com>",
        "Javey <jiawei23716@sina.com>"
    ],
    "bugs": {
        "url": "https://github.com/geejs/gulp-tap/issues"
    },
    "dependencies": {
        "through2": "^2.0.3"
    },
    "description": "Easiest way to tap into a pipeline",
    "devDependencies": {
        "coffee-script": "^1.12.4",
        "coveralls": "^2.13.0",
        "gulp": "^3.9.1",
        "tap": "^10.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "558b302e6b66cf752142a33104c387081a6d5cec",
        "tarball": "https://registry.npmjs.org/gulp-tap/-/gulp-tap-0.4.2.tgz"
    },
    "gitHead": "bbcc5c37bca293c599fb7b7e215cd17601d199b3",
    "homepage": "https://github.com/geejs/gulp-tap",
    "keywords": [
        "tap",
        "gulp",
        "stream"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dotnetcarpenter"
        },
        {
            "name": "mgutz"
        }
    ],
    "name": "gulp-tap",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/geejs/gulp-tap.git"
    },
    "scripts": {
        "coffee": "coffee",
        "posttest": "rm tests/*.js tests/*.js.map",
        "pretest": "coffee --compile --map tests",
        "test": "tap -J tests/*.js",
        "test:coverage": "npm test -- --cov"
    },
    "version": "0.4.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
