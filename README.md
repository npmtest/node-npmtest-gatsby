# npmtest-gatsby

#### basic test coverage for  [gatsby (v0.12.46)](https://github.com/gatsbyjs/gatsby#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gatsby.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gatsby) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gatsby.svg)](https://travis-ci.org/npmtest/node-npmtest-gatsby)

#### React.js Static Site Generator

[![NPM](https://nodei.co/npm/gatsby.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gatsby)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gatsby/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gatsby/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gatsby/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gatsby/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gatsby/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gatsby/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gatsby/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gatsby/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gatsby/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gatsby/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gatsby/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gatsby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gatsby/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gatsby/build/test-report.html](https://npmtest.github.io/node-npmtest-gatsby/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gatsby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gatsby/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gatsby/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gatsby/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gatsby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gatsby/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gatsby/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gatsby/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Mathews"
    },
    "ava": {
        "require": [
            "babel-register"
        ],
        "babel": "inherit"
    },
    "bin": {
        "gatsby": "./bin/gatsby.js"
    },
    "bugs": {
        "url": "https://github.com/gatsbyjs/gatsby/issues"
    },
    "dependencies": {
        "async": "^1.2.1",
        "babel-core": "^6.24.1",
        "babel-loader": "^6.4.1",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-preset-es2015": "^6.24.1",
        "babel-preset-react": "^6.24.1",
        "babel-preset-react-hmre": "^1.1.1",
        "babel-preset-stage-0": "^6.24.1",
        "babel-traverse": "^6.24.1",
        "babylon": "^6.16.1",
        "boom": "^2.7.2",
        "chalk": "^1.1.3",
        "cjsx-loader": "^3.0.0",
        "coffee-loader": "^0.7.3",
        "coffee-script": "^1.12.4",
        "commander": "^2.9.0",
        "css-loader": "^0.28.0",
        "debug": "^2.6.3",
        "detect-port": "^1.1.1",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.11.1",
        "front-matter": "^2.1.0",
        "fs-extra": "^0.30.0",
        "glob": "^7.0.5",
        "global": "^4.3.1",
        "hapi": "^8.5.1",
        "hapi-webpack-plugin": "^1.3.0",
        "highlight.js": "^9.10.0",
        "history": "^2.1.2",
        "html-frontmatter": "^1.6.0",
        "image-webpack-loader": "^2.0.0",
        "invariant": "^2.2.1",
        "json-loader": "^0.5.2",
        "json5": "^0.5.0",
        "less": "^2.7.1",
        "less-loader": "^2.2.0",
        "loader-utils": "^0.2.15",
        "lodash": "^4.15.0",
        "markdown-it": "^7.0.1",
        "markdown-it-replace-link": "^1.0.1",
        "moment": "^2.18.1",
        "negotiator": "^0.6.1",
        "node-cjsx": "^1.0.0",
        "node-libs-browser": "^2.0.0",
        "node-sass": "^4.5.2",
        "null-loader": "^0.1.1",
        "object-assign": "^4.1.0",
        "opn": "^4.0.2",
        "parse-filepath": "^1.0.1",
        "postcss-browser-reporter": "^0.5.0",
        "postcss-cssnext": "2.9.0",
        "postcss-import": "^8.1.2",
        "postcss-loader": "^0.13.0",
        "postcss-reporter": "^1.4.1",
        "prop-types": "^15.5.8",
        "raw-loader": "^0.5.1",
        "react": "^15.5.4",
        "react-document-title": "^2.0.3",
        "react-dom": "^15.5.4",
        "react-hot-loader": "^1.3.0",
        "react-router": "^2.6.1",
        "react-router-scroll": "^0.3.1",
        "sass-loader": "^4.0.0",
        "slash": "^1.0.0",
        "static-site-generator-webpack-plugin": "^2.1.0",
        "style-loader": "^0.16.1",
        "toml": "^2.3.2",
        "toml-loader": "^1.0.0",
        "tracer": "^0.8.3",
        "ts-loader": "^1.2.2",
        "url-loader": "^0.5.8",
        "webpack": "^1.13.2",
        "webpack-configurator": "^0.3.0",
        "webpack-hot-middleware": "^2.17.1",
        "webpack-require": "0.0.16",
        "yaml-loader": "^0.4.0"
    },
    "description": "React.js Static Site Generator",
    "devDependencies": {
        "ava": "0.16",
        "ava-http": "^0.2.1",
        "babel-cli": "^6.24.1",
        "babel-eslint": "^7.2.2",
        "babel-plugin-lodash": "^3.2.8",
        "babel-plugin-transform-flow-strip-types": "^6.8.0",
        "babel-register": "^6.24.1",
        "bluebird": "^3.5.0",
        "cheerio": "^0.22.0",
        "eslint": "^3.19.0",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-config-google": "^0.7.1",
        "eslint-config-prettier": "^1.6.0",
        "eslint-plugin-ava": "^4.2.0",
        "eslint-plugin-flow-vars": "^0.5.0",
        "eslint-plugin-flowtype": "^2.30.4",
        "eslint-plugin-import": "2.2.x",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-prettier": "^2.0.1",
        "eslint-plugin-react": "^6.10.3",
        "flow-bin": "^0.42.0",
        "iflow-debug": "^1.0.15",
        "iflow-lodash": "^1.1.23",
        "iflow-react-router": "^1.1.17",
        "nyc": "^10.1.2",
        "prettier": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5d2cdd46bcc294a8c457e450317cfa9ef943b5b4",
        "tarball": "https://registry.npmjs.org/gatsby/-/gatsby-0.12.46.tgz"
    },
    "engines": {
        "node": ">0.12.0"
    },
    "gitHead": "27b429bdf6fe01d3fcc38b4f724490ee6ee187be",
    "homepage": "https://github.com/gatsbyjs/gatsby#readme",
    "keywords": [
        "blog",
        "generator",
        "jekyll",
        "markdown",
        "react",
        "ssg",
        "website"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "kylemathews"
        }
    ],
    "name": "gatsby",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gatsbyjs/gatsby.git"
    },
    "scripts": {
        "build": "babel lib --out-dir dist/",
        "clean-test-bundles": "find test/ -type f -name bundle.js* -exec rm -rf {} +",
        "format": "prettier --trailing-comma es5 --no-semi --single-quote --write \"lib/**/*.js\" \"test/**/*.js\"",
        "lint": "eslint --ext .js,.jsx --ignore-path .gitignore --ignore-path .eslintignore .",
        "lint:flow": "babel-node scripts/flow-check.js",
        "publish-patch": "npm run build && npm version patch && npm publish; git push; git push --tags",
        "test": "npm run lint && npm run test-node && npm run test-integration",
        "test-coverage": "nyc --reporter=lcov --reporter=text npm test",
        "test-integration": "ava test/integration",
        "test-node": "ava test/utils",
        "watch": "babel -w lib --out-dir dist/"
    },
    "version": "0.12.46"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
