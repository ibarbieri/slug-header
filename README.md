UI Slug Element
===========
Vanilla Javascript component | [View demo](http://ibarbieri.github.io/ui-slug_element/)

You can fix an element when scroll down at determinated position and move it when scroll up.

## Use in your project
```javascript
var elementToFix = new SlugElement('se-element-to-fix', 'height', 46, 84);
```

## How you can use
- Create a new instance of the ui-slug element component.
- The constructor function take four parameters:
	1 - Element to fix class name
	2 - Property to animate
	3 - Property to animate start value
	4 - Property to animate final value


## IE8 fallback
- win.pageYOffset dosen't work in IE8
