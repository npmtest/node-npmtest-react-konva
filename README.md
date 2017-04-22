# npmtest-react-konva

#### basic test coverage for  react-konva (v1.1.3)  [![npm package](https://img.shields.io/npm/v/npmtest-react-konva.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-konva) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-konva.svg)](https://travis-ci.org/npmtest/node-npmtest-react-konva)

#### React binding to canvas element via Konva framework

[![NPM](https://nodei.co/npm/react-konva.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-konva)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-konva/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-konva/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-konva/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-konva/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-konva/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-konva/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-konva/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-konva/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-konva/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-konva/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-konva/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-konva/build/test-report.html](https://npmtest.github.io/node-npmtest-react-konva/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-konva/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-konva/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-konva/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-konva/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-konva/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-konva/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-konva/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-konva/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-konva",
    "description": "React binding to canvas element via Konva framework",
    "version": "1.1.3",
    "keywords": [
        "react",
        "canvas",
        "jsx",
        "konva"
    ],
    "bugs": "https://github.com/lavrton/react-konva/issues",
    "licenses": "BSD-3-Clause",
    "main": "./src/react-konva.js",
    "repository": {
        "type": "git",
        "url": "git@github.com:lavrton/react-konva.git"
    },
    "dependencies": {
        "create-react-class": "^15.5.2",
        "fbjs": "^0.8.12",
        "object-assign": "^4.1.1",
        "prop-types": "^15.5.8"
    },
    "peerDependencies": {
        "react": "~15.5.1",
        "konva": "^1.5.0",
        "react-dom": "~15.5.0"
    },
    "devDependencies": {
        "babel-core": "^6.24.1",
        "babel-loader": "^6.4.1",
        "babel-preset-es2015": "^6.24.1",
        "babel-preset-react": "^6.24.1",
        "babel-register": "^6.24.1",
        "chai": "^3.5.0",
        "enzyme": "^2.8.0",
        "jsdom": "^9.12.0",
        "konva": "^1.5.0",
        "mocha": "^3.2.0",
        "mocha-phantomjs": "^4.1.0",
        "react": "~15.5.1",
        "react-addons-test-utils": "^15.5.1",
        "react-dom": "~15.5.0",
        "react-test-renderer": "^15.5.4",
        "sinon": "^2.1.0",
        "webpack": "^2.3.3",
        "webpack-dev-server": "^2.4.2"
    },
    "scripts": {
        "test:compile": "webpack --config webpack.test.config.js --progress --profile --colors",
        "test:run": "mocha-phantomjs test/index.html",
        "test:clean": "rm ./test/tests.bundle.js",
        "test:watch": "webpack-dev-server --config webpack.test.config.js --progress --profile --colors",
        "test": "npm run test:compile && npm run test:run && npm run test:clean",
        "build": "webpack --progress --profile --colors"
    },
    "typings": "react-konva.d.ts",
    "files": [
        "README.md",
        "src/react-konva.js",
        "react-konva.d.ts"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
