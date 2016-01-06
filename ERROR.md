I am running an AngularJS (Javascript) website and my URL is:  `http://localhost/VRS/portals/` and I don't have access to any resource out side of this domain. When I load up my page, and try to get an address book. I see the following error.

Questions: Where would I look to find the error, and what is is the problem that I'm running into?

````javascript
http://vrs-api.local/v1/user/getAddressBook Failed to load resource: net::ERR_NAME_NOT_RESOLVED
angular.js:10765 OPTIONS http://vrs-api.local/v1/ecommerce/getProducts net::ERR_NAME_NOT_RESOLVED(anonymous function) @ angular.js:10765sendReq @ angular.js:10558serverRequest @ angular.js:10268processQueue @ angular.js:14792(anonymous function) @ angular.js:14808Scope.$eval @ angular.js:16052Scope.$digest @ angular.js:15870Scope.$apply @ angular.js:16160(anonymous function) @ angularAMD.js:152context.execCb @ require.js:1690Module.check @ require.js:865(anonymous function) @ require.js:1140(anonymous function) @ require.js:131(anonymous function) @ require.js:1190each @ require.js:56Module.emit @ require.js:1189Module.check @ require.js:940(anonymous function) @ require.js:1140(anonymous function) @ require.js:131(anonymous function) @ require.js:1190each @ require.js:56Module.emit @ require.js:1189Module.check @ require.js:940Module.enable @ require.js:1177Module.init @ require.js:783callGetModule @ require.js:1204context.completeLoad @ require.js:1583context.onScriptLoad @ require.js:1711
angular.js:12520 ReferenceError: error is not defined
    at productFactory.js:39
    at angular.js:10305
    at processQueue (angular.js:14792)
    at angular.js:14808
    at Scope.$eval (angular.js:16052)
    at Scope.$digest (angular.js:15870)
    at Scope.$apply (angular.js:16160)
    at done (angular.js:10589)
    at completeRequest (angular.js:10787)
    at XMLHttpRequest.requestError (angular.js:10738)(anonymous function) @ angular.js:12520(anonymous function) @ angular.js:9292processQueue @ angular.js:14800(anonymous function) @ angular.js:14808Scope.$eval @ angular.js:16052Scope.$digest @ angular.js:15870Scope.$apply @ angular.js:16160done @ angular.js:10589completeRequest @ angular.js:10787requestError @ angular.js:10738
angular.js:10765 OPTIONS http://vrs-api.local/v1/ecommerce/getCart net::ERR_NAME_NOT_RESOLVED(anonymous function) @ angular.js:10765sendReq @ angular.js:10558serverRequest @ angular.js:10268processQueue @ angular.js:14792(anonymous function) @ angular.js:14808Scope.$eval @ angular.js:16052Scope.$digest @ angular.js:15870Scope.$apply @ angular.js:16160done @ angular.js:10589completeRequest @ angular.js:10787requestLoaded @ angular.js:10728
angular.js:12520 ReferenceError: error is not defined
    at shopCartFactory.js:149
    at angular.js:10305
    at processQueue (angular.js:14792)
    at angular.js:14808
    at Scope.$eval (angular.js:16052)
    at Scope.$digest (angular.js:15870)
    at Scope.$apply (angular.js:16160)
    at done (angular.js:10589)
    at completeRequest (angular.js:10787)
    at XMLHttpRequest.requestError (angular.js:10738)
