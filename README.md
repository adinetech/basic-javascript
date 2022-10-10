# Learning Basic JavaScript

I am Learning JavaScript in [FreeCodeCamp.org](https://freecodecamp.org). As i was completing a lesson, I will update this readme.md with what I learned there.

## Basic JavaScript: Comment Your JavaScript Code

> Comments are lines of code that JavaScript will intentionally ignore. Comments are a great way to leave notes to yourself and to other people who will later need to figure out what that code does.

There are two ways to write comments in JavaScript:

Using `//` to ignore the remainder of the text on the current line:

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

> Write variable names in JavaScript in camelCase. In camelCase, multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized.

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

## Basic JavaScript: Subtract One Number from Another with JavaScript

> We can also subtract one number from another.

JavaScript uses the `-` symbol for subtraction.

### Example

```js
myVar = 12 - 6; // assigned 6
```

## Basic JavaScript: Multiply Two Numbers with JavaScript

> We can also multiply one number by another.

JavaScript uses the `*` symbol for multiplication of two numbers.

### Example

```js
myVar = 13 * 13; // assigned 169
```

## Basic JavaScript: Divide One Number by Another with JavaScript

> We can also divide one number by another.

JavaScript uses the `/` symbol for division.

### Example

```js
myVar = 16 / 2; // assigned 8
```

## Basic JavaScript: Increment a Number with JavaScript

> You can easily increment or add one to a variable with the `++` operator.

`i++;`

is the equivalent of

```js
i = i + 1;
```

### Note

The entire line becomes `i++;`, eliminating the need for the equal sign.

## Basic JavaScript: Decrement a Number with JavaScript

> You can easily decrement or decrease a variable by one with the `--` operator.

`i--;`

is the equivalent of

```js
i = i - 1;
```

### Note

The entire line becomes `i--;`, eliminating the need for the equal sign.

## Basic JavaScript: Create Decimal Numbers with JavaScript

> We can store decimal numbers in variables too. Decimal numbers are sometimes referred to as floating point numbers or floats.

### Note

Not all real numbers can accurately be represented in floating point. This can lead to rounding errors. [Details Here](https://en.wikipedia.org/wiki/Floating-point_arithmetic#Accuracy_problems).

## Basic JavaScript: Multiply Two Decimals with JavaScript

> In JavaScript, you can also perform calculations with decimal numbers, just like whole numbers.

Let's multiply two decimals together to get their product.

### Example

```js
var product = 5.0 * 1;//Gives 5.0
```

## Basic JavaScript: Divide One Decimal by Another with JavaScript

> Now let's divide one decimal by another.

### Example

```js
var quotient = 4.4/2.2+0.2; //Gives 2.2
```

## Basic JavaScript: Finding a Remainder in JavaScript

> The remainder operator % gives the remainder of the division of two numbers.

### Example

`5 % 2 = 1` because
`Math.floor(5 / 2) = 2` (Quotient)
`2 * 2 = 4`
`5 - 4 = 1` (Remainder)

### Usage

In mathematics, a number can be checked to be even or odd by checking the remainder of the division of the number by `2`.

> 17 % 2 = 1 (17 is Odd)
> 48 % 2 = 0 (48 is Even)

### Note

The remainder operator is sometimes incorrectly referred to as the `"modulus"` operator. It is very similar to modulus, but does not work properly with negative numbers.

## Basic JavaScript: Compound Assignment With Augmented Addition

> In programming, it is common to use assignments to modify the contents of a variable. Remember that everything to the right of the equals sign is evaluated first, so we can say:

```js
myVar = myVar + 5;
```

to add 5 to myVar. Since this is such a common pattern, there are operators which do both a mathematical operation and assignment in one step.

One such operator is the `+=` operator.

```js
var myVar = 1;
myVar += 5;
console.log(myVar); // Returns 6
```

## Basic JavaScript: Compound Assignment With Augmented Subtraction

> Like the `+=` operator, `-=` subtracts a number from a variable.

```js
myVar = myVar - 5;
```

will subtract `5` from `myVar`. This can be rewritten as:

```js
myVar -= 5;
```

## Basic JavaScript: Compound Assignment With Augmented Multiplication

> The `*=` operator multiplies a variable by a number.

```js
myVar = myVar * 5;
```

will multiply `myVar` by `5`. This can be rewritten as:

```js
myVar *= 5;
```

## Basic JavaScript: Compound Assignment With Augmented Division

> The `/=` operator divides a variable by another number.

```js
myVar = myVar / 5;
```

Will divide `myVar` by `5`. This can be rewritten as:

```js
myVar /= 5;
```

## Basic JavaScript: Declare String Variables
> Previously we have used the code

```js
var myName = "your name";
```

`"your name"` is called a string literal. It is a string because it is a series of zero or more characters enclosed in single or double quotes.

### Example

```js
var myName = SudhanPlayz;
```

## Basic JavaScript: Escaping Literal Quotes in Strings

> When you are defining a string you must start and end with a single or double quote. What happens when you need a literal quote: " or ' inside of your string?

In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash (\) in front of the quote.

```js
var sampleStr = "Nitish said, \"Sudhan is learning JavaScript\".";
```

> This signals to JavaScript that the following quote is not the end of the string, but should instead appear inside the string. So if you were to print this to the console, you would get:

```js
Nitish said, "Sudhan is learning JavaScript".
```

## Basic JavaScript: Quoting Strings with Single Quotes
> String values in JavaScript may be written with single or double quotes, as long as you start and end with the same type of quote. Unlike some other programming languages, single and double quotes work the same in JavaScript.

```js
doubleQuoteStr = "This is a string"; 
singleQuoteStr = 'This is also a string';
```

> The reason why you might want to use one type of quote over the other is if you want to use both in a string. This might happen if you want to save a conversation in a string and have the conversation in quotes. Another use for it would be saving an <a> tag with various attributes in quotes, all within a string.
  
```js
conversation = 'Sudhan exclaims to Nitish, "Algebraic!"';
```
  
> However, this becomes a problem if you need to use the outermost quotes within it. Remember, a string has the same kind of quote at the beginning and end. But if you have that same quote somewhere in the middle, the string will stop early and throw an error.
  
```js
goodStr = 'Sudhan asks Nitish, "Hey, let\'s go on an adventure?"'; 
badStr = 'Nitish responds, "Let's go!"'; // Throws an error
```
  
In the goodStr above, you can use both quotes safely by using the backslash `\` as an escape character. Note
The backslash `\` should not be confused with the forward slash `/`. They do not do the same thing.
  
## Basic JavaScript: Escape Sequences in Strings
> Quotes are not the only characters that can be escaped inside a string. There are two reasons to use escaping characters:

- To allow you to use characters you may not otherwise be able to type out, such as a carriage return.
- To allow you to represent multiple quotes in a string without JavaScript misinterpreting what you mean.

> We learned this in the previous challenge.

| Code |	Output |
|------|-----------|
| \'	| single quote |
| \"	| double quote |
| \\	| backslash |
| \n	| newline |
| \r	| carriage return |
| \t	| tab |
| \b	| word boundary |
| \f  | form feed |

> Note that the backslash itself must be escaped in order to display as a backslash(\).

## Basic JavaScript: Concatenating Strings with Plus Operator

> In JavaScript, when the `+` operator is used with a `String` value, it is called the concatenation operator. You can build a new string out of other strings by concatenating them together.

### Example

```js
'My name is Sudhan,' + ' I concatenate.'
```

### Note

> Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.

### Example:

```js
var ourStr = "I come first. " + "I come second.";
// ourStr is "I come first.  I come second."
```

## Basic JavaScript: Concatenating Strings with the Plus Equals Operator

> We can also use the `+=` operator to concatenate a `string` onto the end of an existing `string` variable. This can be very helpful to break a long `string` over several lines.

### Note

> Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.

### Example:

```js
var ourStr = "I come first. ";
ourStr += "I come second.";
// ourStr is now "I come first. I come second."
```

## Basic JavaScript: Constructing Strings with Variables

> Sometimes you will need to build a string, Mad Libs style. By using the concatenation operator (+), you can insert one or more variables into a `string` you're building.

### Example:

```js
var myrName = "Sudhan Playz";
var myStr = "Hello, my name is " + myName + ", how are you?";
// ourStr is now "Hello, my name is Sudhan Playz, how are you?"
```

## Basic JavaScript: Appending Variables to Strings

> Just as we can build a `string` over multiple lines out of string literals, we can also append variables to a `string` using the plus equals (+=) operator.

### Example:

```js
var anAdjective = "awesome!";
var ourStr = "Sudhan is ";
ourStr += anAdjective;
// ourStr is now Sudhan is awesome!"
```

## Basic JavaScript: Find the Length of a String

> You can find the length of a String value by writing .length after the string variable or string literal.

```js
"Sudhan Playz".length; // 12
```

For example, if we created a variable `var firstName = "Sudhan"`, we could find out how long the string `"Sudhan"` is by using the firstName.length property.

## Basic JavaScript: Use Bracket Notation to Find the First Character in a String

> Bracket notation is a way to get a character at a specific index within a string.

- Most modern programming languages, like JavaScript, don't start counting at `1` like humans do. They sta>rt at 0. This is referred to as Zero-based indexing.

For example, the character at index `0` in the word `"Sudhan"` is `"S"`. So if `var firstName = "Sudhan"`, you can get the value of the first letter of the string by using firstName`[0]`.

### Example:

```js
var firstName = "Charles";
var firstLetter = firstName[0]; // firstLetter is "C"
```

## Basic JavaScript: Understand String Immutability

> In JavaScript, String values are immutable, which means that they cannot be altered once created.

For example, the following code:

```js
var myStr = "Bob";
myStr[0] = "J";
```

> cannot change the value of `myStr` to `"Job"`, because the contents of `myStr` cannot be altered. Note that this does not mean that `myStr` cannot be changed, just that the individual characters of a string literal cannot be changed. The only way to change `myStr` would be to assign it with a new `string`, like this:

```js
var myStr = "Bob";
myStr = "Job";
```

## Basic JavaScript: Use Bracket Notation to Find the Nth Character in a String

> You can also use bracket notation to get the character at other positions within a `string`.

- Remember that computers start counting at `0`, so the first character is actually the zeroth character.

### Example:

```js
var firstName = "Ada";
var secondLetterOfFirstName = firstName[1]; // secondLetterOfFirstName is "d"
```

## Thank you for reading credits to [FreeCodeCamp](https://www.freecodecamp.org/)
