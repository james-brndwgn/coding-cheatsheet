# Git
Discard unstaged changes
```
git checkout -- .
```

# Javascript

## Arrays
Easily convert NodeList/HTMLCollection to Array with ES6 spread operator
```javascript
const arr = [...document.querySelectorAll('div')];
```

Quickly create a number of items in an Array

```javascript
Array.apply(null, { length: 20 }).map(() => 'foo')
```

## DOM
Programmatically focus an element by adding `tabindex="0"` to it and fire `this.el.focus()`
