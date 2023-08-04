# FUNCTION

Functions are blocks of code that can be saved and run repeatedly. 

- Functions most often have a function name
- They can have as many parameters or no parameters at all
- The should have only one `return` keyword in the function scope or function curly braces
- the function body is where you will place your code or logic

Syntax:

```js
    function functionName(parameter) {

        //function body
    
        //any code you want goes in this function body between the curly braces
        parameter+= '!!'

        // any logic in between the curly braces must be above the return statement
        return `Hello, ${parameter}`
    }
```
