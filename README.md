UI Slug Element
===========
Vanilla Javascript component.

You can fix an element when scroll down at determinated position and move it when scroll up.

## Use in your project
```javascript
var elementToFix = new SlugElement('se-element-to-fix', 'height', 46, 84);
```

## How you can use
- Create a new instance of the ui-slug element component.
- The constructor function take four parameters:
```javascript
new SlugElement(element class name, property to animate, animate start value, animate final value);
```


## To Do
- IE8 fallback: win.pageYOffset doesn't work in IE8.


## License
Licensed under the MIT license.
Copyright (c) 2014 [MercadoLibre](https://github.com/mercadolibre).