---
layout: page
title: Angular2 Quick Notes
---

## Overview

This is a list of userful notes about Angular2 development for my own need. A more completed list can be found at [awesome-angular2](https://github.com/AngularClass/awesome-angular2).

<!-- No more `scope` -->
<!-- performance -->
<!-- universal/isomorphic/server side rendering -->

## Features

#### TypeScript
- [Handbook](http://www.typescriptlang.org/Handbook)
- [ES7 Decorator](https://github.com/wycats/javascript-decorators) and [TypeScript Decorator](https://github.com/Microsoft/TypeScript/issues/2249)

<!-- Compare TypeScript and Flow features https://github.com/Microsoft/TypeScript/issues/1265 -->

#### Change Detection

#### Dependency Injection

#### HTTP(RxJS)
- [rx-book](http://xgrommx.github.io/rx-book/)

#### Zone.js
- [zone.js](https://github.com/angular/zone.js/)

## 1.x vs 2 Syntax Differences

| AngularJS 1.x | Angular2 |
|---------------|----------|
| [`angular.bootstrap`](https://code.angularjs.org/1.4.7/docs/api/ng/function/angular.bootstrap) | [`bootstrap()`](https://angular.io/docs/ts/latest/api/core/bootstrap-function.html)[^bs] |
| `restrict: 'A'` | `selector: '[attribute]'` |
| `restrict: 'E'` | `selector: 'app'` |
| `restrict: 'C'` | `selector: '.class'` |
| `ng-repeat="name in names"` | `*ng-for="#name of names"` |
| `ng-transclude` | `<ng-content>` or [`<content>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/content)[^sd] [^t] [^ve] |
{: .pure-table .pure-table-bordered }

## 1.x to 2 Migration
-  [ngUpgrade](https://github.com/angular/ngUpgrade)


## Footnotes
[^bs]: [Bootstrapping for Angular applications](https://github.com/angular/angular/blob/master/modules/angular2/src/core/application_common.ts#L100)
[^sd]: [Shadow DOM feature in Web Components](http://angular-tips.com/blog/2015/09/migrating-directives-to-angular-2/)
[^t]: [“Transclusion” in Angular 2](http://angular-tips.com/blog/2015/09/migrating-directives-to-angular-2/)
[^ve]: [View Encapsulation in Angular 2](http://blog.thoughtram.io/angular/2015/06/29/shadow-dom-strategies-in-angular2.html)
