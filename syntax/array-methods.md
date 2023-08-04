# ARRAY METHODS

Modifying an array with methods
Let's return to our previous array example and explore some array methods;

```js
const backpack = [
  "boomerang",
  "map",
  "candle",
  "tent",
  "Tums",
  "hairclip",
  "coin pouch",
];

console.log(backpack);
```

## .pop()

You can remove the last item by using a method called `.pop()`.

```js
backpack.pop();
console.log(backpack);
```

## .push()

And add an item to the end by using a method called .push().
What is notable about the .push() method is that it can take a minimum of one argument to an unlimited number of arguments. Let's look at the syntax from the [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push#syntax).

The document demonstrates adding one element, then two, and finally, the `/* ..., */ , elementN` represents that you can continue to add any number of arguments.

```js
push(element0);
push(element0, element1);
push(element0, element1, /* … ,*/ elementN);
```

For now, add just one item to the backpack:

```js
backpack.push("clowder of fierce kittens");
console.log(backpack);
```

### .shift()

You can remove the first item of the array using a method called .`shift()`.

```js
backpack.shift();
console.log(backpack);
```

### .unshift()

You can add an item to the front of the array using a method called
`.unshift()`.

```js
backpack.unshift("bedazzled boomerang");
console.log(backpack);
```

### .slice()

You can also slice your array using the `.slice()` method. In the documentation for `.slice()`, you can see that `.slice()` can take either none, one, or two arguments. It is important to note that regardless of the number of arguments, you must always put them in the same order.

Take the first two items and put them in a new array. The first parameter is the starting position, and the second parameter is the last index position (up to, but not including). Notice that the original array stays the same.

```js
const newBackpack = backpack.slice(0, 2);
console.log(newBackpack);
console.log(backpack);
```

What do you think `.slice()` with no arguments returns? How could you test it?

### .splice()

You can add elements to the middle of your array with the `.splice()` method. The first parameter is the index position where to insert (or remove), the second parameter is how many items to remove (in this case, none), and the last one is what to insert.

```js
backpack.splice(6, 0, "kitten food");
console.log(backpack);
```

Notice that unlike `.slice()`, `.splice()` does change the original array.

### .join()

Finally, you can convert an array into a string. Like the string `.split()` method, you must provide an argument that is a string to provide how the array should be joined.

Join with a space:

```js
const pangramArray = [
  "Amazingly",
  "few",
  "discotheques",
  "provide",
  "jukeboxes.",
];
const pangramString = pangramArray.join(" ");
console.log(pangramString);
// Amazingly few discotheques provide jukeboxes.
```

Join with three `*`:

```js
const starryPangramString = pangramArray.join("***");
console.log(starryPangramString);
// Amazingly***few***discotheques***provide***jukeboxes.
```

**[Syntax Videos & Explanations](https://github.com/10-3-pursuit/10-3-resources/blob/main/javascript-essentials.md)**

[Syntax Choices][def]

[def]: README.md

[Home](https://github.com/10-3-pursuit/10-3-resources/tree/main)