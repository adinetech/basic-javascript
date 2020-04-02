# Learning JavaScript
I am Learning JavaScript in [FreeCodeCamp.org](https://freecodecamp.org). As i was completing a lesson. I will update this readme.md that what I was Studied there.

## Basic JavaScript: Comment Your JavaScript Code
> Comments are lines of code that JavaScript will intentionally ignore. Comments are a great way to leave notes to yourself and to other people who will later need to figure out what that code does.

There are two ways to write comments in JavaScript:

Using `//` will tell JavaScript to ignore the remainder of the text on the current line:

```js
// This is an in-line comment.
```

You can make a multi-line comment beginning with `/*` and ending with `*/`:

```js
/* This is a
multi-line comment */
```
## Basic JavaScript: Declare JavaScript Variables
> In computer science, data is anything that is meaningful to the computer. JavaScript provides seven different data types which are `undefined`, `null`, `boolean`, `string`, `symbol`, `number`, and `object`.

For example, computers distinguish between numbers, such as the number 12, and strings, such as `"12"`, `"dog"`, or `"123 cats"`, which are collections of characters. Computers can perform mathematical operations on a number, but not on a string.

Variables allow computers to store and manipulate data in a dynamic fashion. They do this by using a `"label"` to point to the data rather than using the data itself. Any of the seven data types may be stored in a variable.

Variables are similar to the `x` and `y` variables you use in mathematics, which means they're a simple name to represent the data we want to refer to. Computer `variables` differ from mathematical `variables` in that they can store different values at different times.

We tell JavaScript to create or declare a variable by putting the keyword var in front of it, like so:

```js
var ourName;
```

creates a variable called ourName. In JavaScript we end statements with semicolons. Variable names can be made up of numbers, letters, and $ or _, but may not contain spaces or start with a number.

## Basic JavaScript: Storing Values with the Assignment Operator
> In JavaScript, you can store a value in a variable with the assignment operator.
```js
myVariable = 5;
```
This assigns the Number value `5` to `myVariable`.

Assignment always goes from right to left. Everything to the right of the `=` operator is resolved before the value is assigned to the `variable` to the left of the operator.
```js
myVar = 5;
myNum = myVar;
```
This assigns `5` to `myVar` and then resolves `myVar` to `5` again and assigns it to `myNum`.

## Basic JavaScript: Initializing Variables with the Assignment Operator
> It is common to initialize a variable to an initial value in the same line as it is declared.
```js
var myVar = 0;
```
Creates a new `variable` called `myVar` and assigns it an initial value of `0`.

## Basic JavaScript: Understanding Uninitialized Variables
> When JavaScript variables are declared, they have an initial value of `undefined`. If you do a mathematical operation on an `undefined` variable your result will be `NaN` which means `"Not a Number"`. If you concatenate a string with an `undefined` variable, you will get a literal string of `"undefined"`.

## Basic JavaScript: Understanding Case Sensitivity in Variables
> In JavaScript all variables and function names are case sensitive. This means that capitalization matters.

`MYVAR` is not the same as `MyVar` nor `myvar`. It is possible to have multiple distinct variables with the same name but different casing. It is strongly recommended that for the sake of clarity, you do not use this language feature.

### Best Practice
Write variable names in JavaScript in camelCase. In camelCase, multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized.

### Examples:
```js
var someVariable;
var anotherVariableName;
var thisVariableNameIsSoLong;
```

## Basic JavaScript: Add Two Numbers with JavaScript
> `Number` is a data type in JavaScript which represents numeric data.

Now let's try to add two numbers using JavaScript.

JavaScript uses the `+` symbol as an addition operator when placed between two numbers.

### Example:
```js
myVar = 5 + 10; // assigned 15
```
