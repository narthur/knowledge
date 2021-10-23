# JavaScript

## Snippets

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

## Links

[Best of JavaScript](https://bestofjs.org) - "The best of JavaScript, HTML and CSS"

[Blitz.js](https://blitzjs.com) - "Rails-like framework for monolithic, full-stack React apps — built on Next.js"

[BundlePhobia](https://bundlephobia.com) #webapp - "find the cost of adding a npm package to your bundle"

[Creating a regular expression](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular\_Expressions) #article - "Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the exec and test methods of RegExp, and with the match, replace, search, and split methods of String. This chapter describes JavaScript regular expressions."

[easy-peasy](https://github.com/ctrlplusb/easy-peasy) - "Easy Peasy is an abstraction of Redux, providing a reimagined API that focuses on **developer experience**. It allows you to **quickly** and **easily** manage your state, whilst leveraging the strong **architectural guarantees** and extensive **eco-system** that Redux has to offer."

[egghead.io](https://egghead.io) - "Learn the best JavaScript tools and frameworks from industry pros. Video tutorials for badass web developers."

[Functional programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) #playlist - "This is a collection of the videos from FunFunFunction that is specifically about functional programming in JavaScript"

[Getting creative with the Console API!](https://areknawo.com/getting-creative-with-the-console-api/) #article - "**Debugging** in JavaScript has always been inseparably connected with the [**Console API**](https://developer.mozilla.org/en-US/docs/Web/API/Console), which is most of the time used only through `console.log()`. But, did you know that it doesn't have to be this way? Hasn't `console.log()` already bored you with its **monolithic** output? Do you want to make your logs better, to make them **prettier**? 💅 If so, follow me, as we'll discover how colorful and playful Console API can really be!"

[js2coffee](http://js2.coffee) #webapp - "JavaScript to CoffeeScript compiler."

[Reactiflux](https://www.reactiflux.com) - "We’re a chat community of 80,000+ React JS, React Native, Redux, Jest, Relay and GraphQL developers. We hold Q\&A’s with Facebook Engineers and other developers in the community. Come chat about tech related to React & JavaScript or ask for help!"

[React Native](https://reactnative.dev) - "Learn once, write anywhere."

[RxJS](https://rxjs.dev/guide/overview) - "RxJS is a library for composing asynchronous and event-based programs by using observable sequences. It provides one core type, the [Observable](https://rxjs.dev/guide/observable), satellite types (Observer, Schedulers, Subjects) and operators inspired by [Array#extras](https://developer.mozilla.org/en-US/docs/Web/JavaScript/New\_in\_JavaScript/1.6) (map, filter, reduce, every, etc) to allow handling asynchronous events as collections."

[StateOfJS](https://stateofjs.com) - Yearly surveys on the JavaScript ecosystem

[The Weird History of JavaScript](https://www.youtube.com/watch?v=Sh6lK57Cuk4\&list=PLIilwIraDV2J8hueIWIwvkT3NvfuSChe7\&index=3\&t=11s) #video - "The history of JavaScript over the last 25 years. How did a simple scripting language for Netscape evolve into the world's most widely used programming language?"

[Yup](https://github.com/jquense/yup) - "Yup is a JavaScript schema builder for value parsing and validation. Define a schema, transform a value to match, validate the shape of an existing value, or both. Yup schema are extremely expressive and allow modeling complex, interdependent validations, or value transformations."

[zustand](https://github.com/pmndrs/zustand) - "A small, fast and scaleable bearbones state-management solution. Has a comfy api based on hooks, isn't boilerplatey or opinionated, but still just enough to be explicit and flux-like."

### **Design Patterns**

[Factory Functions in JavaScript](https://www.youtube.com/watch?v=ImwrezYhw4w\&feature=youtu.be) #video

[Inheritance and the prototype chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance\_and\_the\_prototype\_chain) #article - “When it comes to inheritance, JavaScript only has one construct: objects. Each object has a private property which holds a link to another object called its prototype. That prototype object has a prototype of its own, and so on until an object is reached with null as its prototype. By definition, null has no prototype, and acts as the final link in this prototype chain.” 👍

[JavaScript Design Patterns](https://seesparkbox.com/foundry/javascript\_design\_patterns) #article - “Intentional code is the best code. Patrick shares how to apply design patterns to write cleaner JavaScript.” 👍 (It’s Prototype pattern actually seems to be the classical pattern of object instantiation in JavaScript.)

[Learning JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/) #book - Read online for free. “Design patterns are reusable solutions to commonly occurring problems in software design. They are both exciting and a fascinating topic to explore in any programming language.”

[Modular Javascript - Prototypal Pattern vs Classical OOP in JS](https://www.youtube.com/watch?v=doXpW5AD60Q) #video - “While many JS devs still use classical OOP, many have switched to the prototypal pattern for Module Inheritance and Instantiation.  Here's the prototypal pattern for JS and why some devs find it simpler to use.”

[Writing Maintainable and Readable Javascript: Design Patterns](https://www.javascriptjanuary.com/blog/writing-maintainable-and-readable-javascript-design-patterns) #article - “Over the lifespan of Javascript, many design patterns have been made and tested by a large number of developers using javascript. In this article, we would explain the common design patterns used by javascript developers.”

## TypeScript

[TypeScript: Typed JavaScript at Any Scale.](https://www.typescriptlang.org)

[Typing Destructured Object Parameters in TypeScript](https://mariusschulz.com/blog/typing-destructured-object-parameters-in-typescript) #article

## Sources

[Fun Fun Function](https://www.youtube.com/channel/UCO1cgjhGzsSYb1rsB4bFe4Q) #channel - "I’m Mattias Petter Johansson, mpj for short. I’ve been a full-time programmer for about ten years. Among others, I've worked for Absolut Vodka, Blackberry and Spotify."

[JSConf](https://www.youtube.com/channel/UCzoVCacndDCfGDf41P-z0iA) #channel - "The JSConf YouTube Channel. JSConf is a series of JavaScript conferences from around the world and here we release the conference talk videos for free as fast as we can after every event. Topics include JavaScript, HTML5, CSS, node.js, robotics, etc."
