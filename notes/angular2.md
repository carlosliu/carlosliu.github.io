---
layout: page
title: Angular2 Quick Notes
---

# Overview
<!-- No more `scope` -->

# Features

### HTTP/RxJS

# 1.x to 2

| AngularJS 1.x | Angular2 |
|---------------|----------|
| [`angular.bootstrap`](https://code.angularjs.org/1.4.7/docs/api/ng/function/angular.bootstrap) | [`bootstrap()`](https://angular.io/docs/ts/latest/api/core/bootstrap-function.html)[^2] |
| `restrict: 'A'` | `selector: '[attribute]'` |
| `restrict: 'E'` | `selector: 'app'` |
| `restrict: 'C'` | `selector: '.class'` |
| `ng-transclude` | `<ng-content>`[^transclusion] or [`<content>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/content)[^shadowdom] |
{: .pure-table .pure-table-striped }

# Resources
1. [awesome-angular2](https://github.com/AngularClass/awesome-angular2)
1. [Angular2-Learning](https://github.com/jmcunningham/AngularJS2-Learning)


[^2]: [Bootstrapping for Angular applications](https://github.com/angular/angular/blob/master/modules/angular2/src/core/application_common.ts#L100)
[^transclusion]: [“Transclusion” in Angular 2](http://angular-tips.com/blog/2015/09/migrating-directives-to-angular-2/)
[^shadowdom]: [Shadow DOM feature in Web Components](http://angular-tips.com/blog/2015/09/migrating-directives-to-angular-2/)
