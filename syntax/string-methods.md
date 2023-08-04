# STRING METHODS


### .toUpperCase()

You can make all your text capital letters using a string method.

Google for and then look at the documentation at MDN. First, you may notice that this method says `String.prototype.toUpperCase()`. When you see this syntax (with `prototype` in the middle), you can attach the function to your value. This is in contrast to the Math method, where you have to start with the word `Math` and then add `.something()`. You'll learn more about the keyword prototype later in the course.

As you read the documentation, there are a few sections. They generally show a pattern that shows a demo, then the syntax and some other sections that may or may not have the information you are looking for. Finding what you need in documentation is a skill you'll build over time.

Let's look at the code below, and before running it, take a moment to think about the output. What will happen to the comma and period? Will the code error be because of these characters? Then run the code and compare and contrast what you thought would happen with what did happen. This process will help you gain understanding and learn to use new methods faster and better.

```js
const pangram = "When zombies arrive, quickly fax judge Pat.";

console.log(pangram.toUpperCase());
```

### .replace() and .replaceAll()

You can replace some text using the `.replace()` method. Let's say you want to change the text `To be or not to be` to read `To code or not to code`.

Let's look at [the documentation.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace#syntax)

What this method shows is that it takes two parameters `pattern` and `replacement`. What do those words mean? Please take a moment to put it in your own words.

Let's look at the code below:

```js
let myQuote = `To be or not to be`;
myQuote = myQuote.replace("be", "code");
console.log(myQuote);
// To code or not to be
```

The `.replace()` method goes after your value of `myQuote`. However, this one only changed the first `be`. Your next move would be to look and see if another method fits your needs or to google how to do what you want to do.

In this case, there is another method that will change all the instances.

```js
myCompleteQuote = myQuote.replaceAll("be", "code");
console.log(myCompleteQuote);
// To code or not to code
```

### .split()

Here is another string method where you can split the string into an array. `.split()` takes one argument, the character you want to split the words apart with. If you wish to split every letter individually, you will put an empty string. However, if you want every word as an array item, you would pass a quoted space.

Using empty string:

```js
const stringToArray = "The quick brown fox jumped over the lazy dog";
console.log(stringToArray.split(""));
// [
// 'T', 'h', 'e', ' ', 'q', 'u', 'i',
// 'c', 'k', ' ', 'b', 'r', 'o', 'w',
// 'n', ' ', 'f', 'o', 'x', ' ', 'j',
// 'u', 'm', 'p', 'e', 'd', ' ', 'o',
// 'v', 'e', 'r', ' ', 't', 'h', 'e',
// ' ', 'l', 'a', 'z', 'y', ' ', 'd',
// 'o', 'g'
// ]
```

Using a space:

```js
console.log(stringToArray.split(" "));
// [
// 'The', 'quick',
// 'brown', 'fox',
// 'jumped', 'over',
// 'the', 'lazy',
// 'dog'
// ]
```

**[Syntax Videos & Explanations](https://github.com/10-3-pursuit/10-3-resources/blob/main/javascript-essentials.md)**

[Syntax Options][def]

[def]: README.md

[Home](https://github.com/10-3-pursuit/10-3-resources/tree/main)