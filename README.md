no.minutvikler.js.jquery-scrollto
=================================

A jquery-plugin to simplify anchor-onclick-animation-scrolling to href-id.

Interface
=========

```javascript
var scrollTo = function(speed, offset, easing, callback);
```

Example usage
=============

```html
<a href="#target-section-id" onclick="$(this).scrollTo('slow', 100, 'swing', function() { console.log('Complete'); });return false;"> Click me to scroll</a>
```
