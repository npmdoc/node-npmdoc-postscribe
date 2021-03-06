# npmdoc-postscribe

#### api documentation for  [postscribe (v2.0.8)](https://krux.github.io/postscribe)  [![npm package](https://img.shields.io/npm/v/npmdoc-postscribe.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-postscribe) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-postscribe.svg)](https://travis-ci.org/npmdoc/node-npmdoc-postscribe)

#### Asynchronously write javascript, even with document.write.

[![NPM](https://nodei.co/npm/postscribe.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postscribe)

- [https://npmdoc.github.io/node-npmdoc-postscribe/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postscribe/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postscribe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postscribe/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-postscribe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-postscribe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "postscribe",
    "description": "Asynchronously write javascript, even with document.write.",
    "homepage": "https://krux.github.io/postscribe",
    "bugs": "https://github.com/krux/postscribe/issues",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git://github.com/krux/postscribe.git"
    },
    "keywords": [
        "document.write",
        "tag writer",
        "asynchronous",
        "javascript",
        "after load"
    ],
    "author": {
        "name": "Derek Brans",
        "web": "http://github.com/dbrans"
    },
    "maintainers": [
        {
            "name": "Joshua Newman",
            "web": "https://github.com/jnewman"
        }
    ],
    "main": "dist/postscribe.js",
    "browser": "dist/postscribe.js",
    "dependencies": {
        "prescribe": ">=1.1.2"
    },
    "devDependencies": {
        "babel-core": "6.18.2",
        "babel-eslint": "7.1.0",
        "babel-loader": "6.2.7",
        "babel-plugin-transform-es3-member-expression-literals": "6.8.0",
        "babel-plugin-transform-es3-property-literals": "6.8.0",
        "babel-plugin-transform-object-assign": "6.8.0",
        "babel-preset-es2015": "6.18.0",
        "babel-preset-es2015-loose": "8.0.0",
        "babel-register": "6.18.0",
        "babelify": "7.3.0",
        "cz-conventional-changelog": "1.2.0",
        "del": "2.2.2",
        "eslint": "3.9.0",
        "expect.js": "0.3.1",
        "gulp": "3.9.1",
        "gulp-babel": "6.1.2",
        "gulp-esdoc": "0.3.0",
        "gulp-eslint": "3.0.1",
        "gulp-filter": "4.0.0",
        "gulp-header": "1.8.8",
        "gulp-jscs": "4.0.0",
        "gulp-rename": "1.2.2",
        "gulp-strip-debug": "1.1.0",
        "gulp-uglify": "2.0.0",
        "isparta": "4.0.0",
        "isparta-loader": "2.0.0",
        "jquery": "1.12.4",
        "jscs": "3.0.7",
        "json-loader": "0.5.4",
        "karma": "1.3.0",
        "karma-babel-preprocessor": "6.0.1",
        "karma-coverage": "1.1.1",
        "karma-coveralls": "1.1.2",
        "karma-expect": "1.1.3",
        "karma-mocha": "1.3.0",
        "karma-mocha-reporter": "2.2.1",
        "karma-phantomjs-launcher": "1.0.2",
        "karma-sauce-launcher": "1.1.0",
        "karma-sinon": "1.0.5",
        "karma-sourcemap-loader": "0.3.7",
        "karma-webpack": "1.8.0",
        "mocha": "3.1.2",
        "phantomjs-prebuilt": "2.1.13",
        "semantic-release": "^6.3.2",
        "sinon": "1.17.6",
        "watchify": "3.7.0",
        "webpack": "1.13.3",
        "webpack-dev-server": "1.16.2",
        "webpack-stream": "3.2.0"
    },
    "config": {
        "ports": {
            "cdn": "8080"
        },
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "babel": {
        "presets": [
            "es2015-loose"
        ],
        "plugins": [
            "transform-es3-member-expression-literals",
            "transform-es3-property-literals",
            "transform-object-assign"
        ],
        "comments": true,
        "compact": false
    },
    "scripts": {
        "build": "gulp build",
        "clean": "gulp clean",
        "doc": "gulp doc",
        "lint": "gulp lint",
        "semantic-release": "semantic-release pre && gulp build && npm publish && semantic-release post",
        "start": "gulp serve",
        "tdd": "gulp tdd",
        "tdd:coverage": "gulp tdd:coverage",
        "test": "gulp test",
        "test:ci": "gulp test:ci",
        "test:cross-browser": "gulp test:cross-browser",
        "test:debug": "gulp test:debug",
        "test:nocoverage": "gulp test:nocoverage"
    },
    "version": "2.0.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
