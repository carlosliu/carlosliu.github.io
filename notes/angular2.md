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
| [^1] | `bootstrap()`[^2] |
| `restrict: 'A'` | `selector: '[attribute]'` |
| `restrict: 'E'` | `selector: 'app'` |
| `restrict: 'C'` | `selector: '.class'` |
| `ng-transclude` | `<ng-content>` or `<content>`[^content] |

# Resources
1. [awesome-angular2](https://github.com/AngularClass/awesome-angular2)
1. [Angular2-Learning](https://github.com/jmcunningham/AngularJS2-Learning)


[^1]: https://code.angularjs.org/1.4.7/docs/guide/bootstrap
[^2]: https://github.com/angular/angular/blob/master/modules/angular2/src/core/application_common.ts#L100
[^content]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/content
