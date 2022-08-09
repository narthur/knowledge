# Snippets

Referencing `this` inside a callback can be tricky, since `this` refers to the context where the function is called, not where it is defined. To explicitly bind `this` to the defining context, [use the `bind()` function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global\_Objects/Function/bind):

```javascript
myFunction(callback.bind(this))
```

To find the first element of an array satisfying some criteria, [use Array.prototype.find()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global\_Objects/Array/find). If you just need the index, [use .findIndex instead](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global\_Objects/Array/findIndex). ([via StackOverflow](https://stackoverflow.com/a/18520276/937377))

```javascript
var array1 = [5, 12, 8, 130, 44];

var found = array1.find(function(element) {
  return element > 10;
});

console.log(found);
// expected output: 12
```

Log the current stack to the console:

```
console.log(new Error().stack);
```
