---
layout: page
title: Angular2 Quick Notes
---

## Overview
<!-- No more `scope` -->
<!-- performance -->
<!-- universal/isomorphic/server side rendering -->

## Features

#### TypeScript

#### Change Detection

#### Dependency Injection

#### HTTP/RxJS

#### Zone.js

## 1.x vs 2 Differences

| AngularJS 1.x | Angular2 |
|---------------|----------|
| [`angular.bootstrap`](https://code.angularjs.org/1.4.7/docs/api/ng/function/angular.bootstrap) | [`bootstrap()`](https://angular.io/docs/ts/latest/api/core/bootstrap-function.html)[^bs] |
| `restrict: 'A'` | `selector: '[attribute]'` |
| `restrict: 'E'` | `selector: 'app'` |
| `restrict: 'C'` | `selector: '.class'` |
| `ng-transclude` | `<ng-content>`[^t] or [`<content>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/content)[^sd] |
{: .pure-table .pure-table-bordered }

## 1.x to 2 Migration
-  [ngUpgrade](https://github.com/angular/ngUpgrade)

## Resources
- [awesome-angular2](https://github.com/AngularClass/awesome-angular2)

## Footnotes
[^bs]: [Bootstrapping for Angular applications](https://github.com/angular/angular/blob/master/modules/angular2/src/core/application_common.ts#L100)
[^t]: [“Transclusion” in Angular 2](http://angular-tips.com/blog/2015/09/migrating-directives-to-angular-2/)
[^sd]: [Shadow DOM feature in Web Components](http://angular-tips.com/blog/2015/09/migrating-directives-to-angular-2/)
