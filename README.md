# cordova-plugin-demo
test-demo
插件调用    
<ion-content ng-controller="PluginCtrl">     
<button class="button" ng-click="invokeJsPlugin()">Test Plugin</button>   
</ion-content>  
方法的定义：  
.controller('PluginCtrl', function ($scope) {
  $scope.invokeJsPlugin = function () { 
    JsPlugin.alert();    
  }; 
})
