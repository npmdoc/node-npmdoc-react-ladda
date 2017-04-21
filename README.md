# npmdoc-react-ladda

#### api documentation for  [react-ladda (v5.0.6)](https://github.com/jsdir/react-ladda#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-ladda.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-ladda) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-ladda.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-ladda)

#### React wrapper for Ladda buttons

[![NPM](https://nodei.co/npm/react-ladda.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-ladda)

- [https://npmdoc.github.io/node-npmdoc-react-ladda/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-ladda/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-ladda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-ladda/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-ladda/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-ladda/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-ladda",
    "version": "5.0.6",
    "description": "React wrapper for Ladda buttons",
    "main": "dist/index.js",
    "scripts": {
        "watch": "./node_modules/.bin/mocha -w --watch-extensions=jsx test/.setup.js test/**/*-test.jsx",
        "test": "./node_modules/.bin/mocha test/.setup.js test/**/*-test.jsx",
        "lint": "./node_modules/.bin/eslint src/**/* test/**/*",
        "build": "npm run lint && ./node_modules/.bin/babel src --out-dir dist",
        "prepublish": "npm run build"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jsdir/react-ladda.git"
    },
    "keywords": [
        "react",
        "component",
        "boilerplate"
    ],
    "author": "Jason Sommer",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/jsdir/react-ladda/issues"
    },
    "homepage": "https://github.com/jsdir/react-ladda#readme",
    "dependencies": {
        "ladda": "^1.0.0"
    },
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-eslint": "^6.1.2",
        "babel-plugin-transform-flow-strip-types": "^6.8.0",
        "babel-plugin-transform-regenerator": "^6.4.4",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babel-preset-stage-0": "^6.3.13",
        "babel-register": "^6.4.3",
        "chai": "^3.5.0",
        "chai-enzyme": "^0.5.1",
        "enzyme": "^2.0.0",
        "eslint": "^3.7.0",
        "eslint-config-airbnb": "^12.0.0",
        "eslint-plugin-import": "^1.16.0",
        "eslint-plugin-jsx-a11y": "^2.2.2",
        "eslint-plugin-react": "^6.3.0",
        "jsdom": "^8.0.1",
        "mocha": "^2.4.5",
        "react-addons-test-utils": "^15.3.1",
        "sinon": "^1.17.5",
        "sinon-chai": "^2.8.0",
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
