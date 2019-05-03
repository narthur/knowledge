# JavaScript

## Snippets

Referencing `this` inside a callback can be tricky, since `this` refers to the context where the function is called, not where it is defined. To explicitly bind `this` to the defining context, [use the `bind()` function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind):

```javascript
myFunction(callback.bind(this))
```

To find the first element of an array satisfying some criteria, [use Array.prototype.find\(\)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find). If you just need the index, [use .findIndex instead](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex). \([via StackOverflow](https://stackoverflow.com/a/18520276/937377)\)

```javascript
var array1 = [5, 12, 8, 130, 44];

var found = array1.find(function(element) {
  return element > 10;
});

console.log(found);
// expected output: 12
```

## Links

[Creating a regular expression](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions) \#article - "Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the exec and test methods of RegExp, and with the match, replace, search, and split methods of String. This chapter describes JavaScript regular expressions."

[Functional programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) \#playlist - "This is a collection of the videos from FunFunFunction that is specifically about functional programming in JavaScript"

[Getting creative with the Console API!](https://areknawo.com/getting-creative-with-the-console-api/) \#article - "**Debugging** in JavaScript has always been inseparably connected with the [**Console API**](https://developer.mozilla.org/en-US/docs/Web/API/Console), which is most of the time used only through `console.log()`. But, did you know that it doesn't have to be this way? Hasn't `console.log()` already bored you with its **monolithic** output? Do you want to make your logs better, to make them **prettier**? 💅 If so, follow me, as we'll discover how colorful and playful Console API can really be!"

[js2coffee](http://js2.coffee/) \#webapp - "JavaScript to CoffeeScript compiler."

## Sources

[Fun Fun Function](https://www.youtube.com/channel/UCO1cgjhGzsSYb1rsB4bFe4Q) \#channel - "I’m Mattias Petter Johansson, mpj for short. I’ve been a full-time programmer for about ten years. Among others, I've worked for Absolut Vodka, Blackberry and Spotify."

