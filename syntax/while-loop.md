# WHILE LOOP

A while loop is similar to an if statement in that we will check if some condition is true. Unlike an if statement, we will execute the code block following the while loop, again and again, as long as the condition is true. Whenever we reach the bottom of the code block, we back up and check the condition again.

```js

    let num = 1;

    while (num <= 10) {
        console.log("the number is: " + num);

        num += 1; // alway remember to increment the num variable or you will create an infinite loop
    }

```

**[Syntax Videos & Explanations](https://github.com/10-3-pursuit/10-3-resources/blob/main/javascript-essentials.md)**