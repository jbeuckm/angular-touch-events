# angular-touch-events
Directives that access lower level touch events, ie. touchstart, touchmove, touchleave, touchend 

### Usage ###

```javascript
angular.module('myModule', ['touch-events'])...
```
```html
<div ng-touchstart="myHandler($event)">Press Me</div>
```
