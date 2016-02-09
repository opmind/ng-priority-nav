# ng-priority-nav
A Priority Navigation component for AngularJs

[DEMO](http://lewie6.github.io/ng-priority-nav/) (need to improve this!)


AngularJs directive that turns your navigation into the priority navigation design pattern.

No dependancies.

Download the source from dist/ng-priority-nav.min.js and include it in your project, then include the module
```
angular.module('app', ['ngPriorityNav']);
```
Or use Bower (coming soon)

# Example usage:

Simple usage:
```HTML
<div priority-nav>
  <div ng-repeat="navItem in navItems">{{navItem.title}}</div>
</div>
```
Or Dynamic?... this will listen for changes to your model and re-apply the directive:
```HTML
<div priority-nav="{{navItems}}">
  <div ng-repeat="navItem in navItems">{{navItem.title}}</div>
</div>
```
