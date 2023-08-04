# IF - CONDITIONAL


Syntax:

### IF

```js
if(conditionalStatement){logic}

```
- conditional statement is always in parentheses and must evaluate to true or false
- logic must go between the curly braces

### ELSE IF

```js
else if(conditionalStatement){logic}

```

- else if MUST have parenthesis
- conditional statement is always in parentheses and must evaluate to true or false
- logic must go between the curly braces

### ELSE

```js
else{ logic }

```
- else does not have parenthesis only curly braces
- it is considered the default if all other conditions are false


Example:
```js
    const temperatureInFahrenheit = 70;

    if (temperatureInFahrenheit <= 32) {
    console.log("It's freezing cold!");
    } else if (temperatureInFahrenheit <= 50) {
    console.log("It's pretty cold outside!");
    } else if (temperatureInFahrenheit <= 65) {
    console.log("It might be a bit chilly out today.");
    } else if (temperatureInFahrenheit <= 80) {
    console.log("Wow, it is really warm today!");
    } else {
    console.log("It's so hot!");
    }

```