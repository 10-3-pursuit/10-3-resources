# Truthy and falsy values

While there are only two boolean values, other values (strings, numbers) can have a truthy or falsy value associated with them.

For example, the number 0 is falsy:

```js
// You should NOT see this console.log
if (0) {
  console.log("This value is not truthy");
}
```

You can also use the not operator to get the opposite value evaluated:

```js
// You should see this console.log
if (!0) {
  console.log("This value is truthy");
}
```

Most values in JavaScript are truthy. Here is are some common ones that are falsy:

- `0`
- `""` (empty string)
- `null`
- `undefined`
- `NaN`

If you are not sure if a value is truthy or falsy you have two options.

You can test it by using two `!!`

```js
console.log(!!0);
// false
console.log(!!1);
// true
```

Or you can look at a truth table. The following [table](https://dorey.github.io/JavaScript-Equality-Table/) has three tabs:

- Loose equality (does not check whether the type of data is the same, in this case `"3" == 3` is true).
- Strict equality(checks whether the type of data is the same, in this case `"3" === 3` is false).
- if statement evaluations (determines if the code in the block should run or not).