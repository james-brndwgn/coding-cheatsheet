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

## DOM
Programmatically focus an element by adding `tabindex="0"` to it and fire `this.el.focus()`
