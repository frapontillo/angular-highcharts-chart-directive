angular-highcharts-chart-directive [![Build Status](https://travis-ci.org/frapontillo/angular-highcharts.png?branch=develop)](https://travis-ci.org/frapontillo/angular-highcharts?branch=develop)
==================================

Angular Highcharts - Easy Highcharts for your AngularJS app!

##How to use

###Install
To install the files with bower, simply call

```shell
$ bower install angular-highcharts
```

Or you can simply copy the file you want to include from the `dist` folder.

###Reference in AngularJS

Reference the module by including it into the injection array of your app:

```javascript
angular.module('myApp', ['frapontillo.highcharts']);
```

##Test and build

```shell
$ npm install grunt-cli bower -g
$ npm install
$ bower install
$ grunt test
$ grunt build
```