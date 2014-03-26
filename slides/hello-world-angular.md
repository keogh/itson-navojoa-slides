##  Hello World Angular.js

``` Javascript
angular.module('app', [])
  .controller('MainCtrl', function ($scope) {
    $scope.world = 'Mundo';
  });
```

``` html
<html ng-app="app">
  <body ng-controller="MainCtrl">
    Hello {{world}}!
  </body>
</html>
```
