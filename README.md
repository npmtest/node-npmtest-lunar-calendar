# npmtest-lunar-calendar

#### basic test coverage for  lunar-calendar (v0.1.4)  [![npm package](https://img.shields.io/npm/v/npmtest-lunar-calendar.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lunar-calendar) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lunar-calendar.svg)](https://travis-ci.org/npmtest/node-npmtest-lunar-calendar)

#### 农历（阴历）万年历，是一款支持Node.js和浏览器端使用的全功能农历和公历日历类库。支持农历与公历之间相互转换，含有二十四节气，天干地支纪年纪月纪日，生肖属相，公历节假日及农历传统节假日信息等功能。自带2013-2014节假日安排数据，并可自行配置。带有黄历数据，可自行选择配置。支持1891-2100年。

[![NPM](https://nodei.co/npm/lunar-calendar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lunar-calendar)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lunar-calendar/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lunar-calendar/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lunar-calendar/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lunar-calendar/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lunar-calendar/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lunar-calendar/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lunar-calendar/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lunar-calendar/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lunar-calendar/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lunar-calendar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lunar-calendar/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lunar-calendar/build/test-report.html](https://npmtest.github.io/node-npmtest-lunar-calendar/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lunar-calendar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lunar-calendar/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lunar-calendar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lunar-calendar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lunar-calendar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lunar-calendar/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lunar-calendar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lunar-calendar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "JasonZhou <zzyss86@qq.com> (http://www.2fz1.com/)",
    "name": "lunar-calendar",
    "description": "农历（阴历）万年历，是一款支持Node.js和浏览器端使用的全功能农历和公历日历类库。支持农历与公历之间相互转换，含有二十四节气，天干地支纪年纪月纪日，生肖属相，公历节假日及农历传统节假日信息等功能。自带2013-2014节假日安排数据，并可自行配置。带有黄历数据，可自行选择配置。支持1891-2100年。",
    "keywords": [
        "chinese lunar",
        "lunar",
        "农历",
        "阴历",
        "万年历",
        "LunarCalendar",
        "calendar"
    ],
    "version": "0.1.4",
    "repository": {
        "type": "git",
        "url": "https://github.com/zzyss86/LunarCalendar.git"
    },
    "main": "./lib/LunarCalendar.js",
    "engines": {
        "node": "*"
    },
    "dependencies": {},
    "devDependencies": {
        "grunt": "0.4.2",
        "grunt-contrib-uglify": "0.3.2",
        "mocha": "*",
        "expect.js": "*"
    },
    "scripts": {
        "test": "make test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
