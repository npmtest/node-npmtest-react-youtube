# npmtest-react-youtube

#### basic test coverage for  [react-youtube (v7.4.0)](https://github.com/compedit/react-youtube)  [![npm package](https://img.shields.io/npm/v/npmtest-react-youtube.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-youtube) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-youtube.svg)](https://travis-ci.org/npmtest/node-npmtest-react-youtube)

#### react.js powered YouTube player component

[![NPM](https://nodei.co/npm/react-youtube.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-youtube)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-youtube/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-youtube/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-youtube/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-youtube/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-youtube/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-youtube/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-youtube/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-youtube/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-youtube/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-youtube/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-youtube/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-youtube/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-youtube/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-youtube/build/test-report.html](https://npmtest.github.io/node-npmtest-react-youtube/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-youtube/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-youtube/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-youtube/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-youtube/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-youtube/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-youtube/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-youtube/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-youtube/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "troy betz"
    },
    "bugs": {
        "url": "https://github.com/compedit/react-youtube/issues"
    },
    "dependencies": {
        "lodash.isequal": "^4.4.0",
        "prop-types": "^15.5.3",
        "youtube-player": "^4.2.3"
    },
    "description": "react.js powered YouTube player component",
    "devDependencies": {
        "babel-cli": "^6.16.0",
        "babel-core": "^6.16.0",
        "babel-eslint": "^7.0.0",
        "babel-loader": "^6.2.5",
        "babel-preset-es2015": "^6.16.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "cross-env": "^4.0.0",
        "eslint": "^3.6.1",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-plugin-import": "^2.0.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.3.0",
        "expect": "^1.20.2",
        "jsdom": "^9.5.0",
        "lodash.assign": "^4.2.0",
        "mocha": "^3.1.0",
        "npm-run-all": "^4.0.2",
        "proxyquire": "^1.7.10",
        "react": "^15.3.2",
        "react-dom": "^15.3.2",
        "webpack": "^2.3.3",
        "webpack-dev-server": "^2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "d346c30ec77eec61871e8c0784cef2cb2c69b63d",
        "tarball": "https://registry.npmjs.org/react-youtube/-/react-youtube-7.4.0.tgz"
    },
    "gitHead": "37b7629dd3d662775f92403e1e20050ba02018c2",
    "homepage": "https://github.com/compedit/react-youtube",
    "keywords": [
        "react",
        "youtube",
        "player",
        "react-component"
    ],
    "license": "MIT",
    "main": "dist/YouTube.js",
    "maintainers": [
        {
            "name": "tjallingt"
        },
        {
            "name": "troybetz"
        }
    ],
    "module": "es/YouTube.js",
    "name": "react-youtube",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.14.1"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/compedit/react-youtube.git"
    },
    "scripts": {
        "compile": "npm-run-all --parallel compile:cjs compile:es",
        "compile:cjs": "babel src --out-dir dist",
        "compile:es": "cross-env BABEL_ENV=es babel src --out-dir es",
        "example": "webpack-dev-server --config example/webpack.config.js",
        "lint": "eslint src",
        "prepublish": "npm run compile",
        "test": "mocha"
    },
    "version": "7.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
