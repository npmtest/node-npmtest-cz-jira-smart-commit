# npmtest-cz-jira-smart-commit

#### test coverage for  [cz-jira-smart-commit (v2.0.1)](https://github.com/commitizen/cz-jira-smart-commit#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cz-jira-smart-commit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cz-jira-smart-commit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cz-jira-smart-commit.svg)](https://travis-ci.org/npmtest/node-npmtest-cz-jira-smart-commit)

#### A commitizen adapter for Jira smart commits

[![NPM](https://nodei.co/npm/cz-jira-smart-commit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cz-jira-smart-commit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cz-jira-smart-commit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cz-jira-smart-commit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/test-report.html](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cz-jira-smart-commit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cz-jira-smart-commit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cz-jira-smart-commit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cz-jira-smart-commit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cz-jira-smart-commit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kent C. Dodds",
        "url": "http://kentcdodds.com/"
    },
    "bugs": {
        "url": "https://github.com/commitizen/cz-jira-smart-commit/issues"
    },
    "contributors": [
        {
            "name": "Jane Kim",
            "url": "http://janekim.me"
        }
    ],
    "dependencies": {
        "inquirer": "^1.1.3"
    },
    "description": "A commitizen adapter for Jira smart commits",
    "devDependencies": {
        "babel": "5.8.21",
        "chai": "3.2.0",
        "mocha": "2.2.5",
        "nodemon": "1.4.0",
        "proxyquire": "^1.7.10",
        "sinon": "1.15.4",
        "sinon-chai": "2.8.0",
        "with-package": "0.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "992e9050be3eb6697e2ccb4edc336e532b10f613",
        "tarball": "https://registry.npmjs.org/cz-jira-smart-commit/-/cz-jira-smart-commit-2.0.1.tgz"
    },
    "gitHead": "4c95b1026b76b4aef58e3da4ae0cb9f0383c413a",
    "homepage": "https://github.com/commitizen/cz-jira-smart-commit#readme",
    "keywords": [
        "commitizen",
        "commitizen adapter",
        "jira",
        "jira smart commit"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "commitizen-bot"
        },
        {
            "name": "jimthedev"
        },
        {
            "name": "kentcdodds"
        },
        {
            "name": "linusu"
        }
    ],
    "name": "cz-jira-smart-commit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/commitizen/cz-jira-smart-commit.git"
    },
    "scripts": {
        "release": "npm run test && with-package git commit -am pkg.version && with-package git tag pkg.version && git push && npm publish && git push --tags",
        "release:beta": "npm run release && npm run tag:beta",
        "start": "nodemon --exec \"npm run test\"",
        "tag:beta": "with-package npm dist-tag add pkg.name@pkg.version beta",
        "test": "mocha index.test --compilers js:babel/register"
    },
    "version": "2.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
