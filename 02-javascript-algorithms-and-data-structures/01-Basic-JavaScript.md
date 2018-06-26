## Basic JavaScript

> JavaScript is a high-level programming language that all modern web browsers support.
It is also one of the core technologies of the web, along with HTML and CSS that you may have learned previously.
This section will cover basic JavaScript programming concepts, which range from variables and arithmetic to objects and loops.

- [Comment your JavaScript code](#comment-your-javascript-code)
- [Declare JavaScript variables](#declare-javascript-variables)
- [Storing values with the assignment operator](#storing-values-with-the-assignment-operator)
- [Initializing variables with the assignment operator](#initializing-variables-with-the-assignment-operator)
- [Understanding uninitialized variables](#understanding-uninitialized-variables)
- [Understanding case sensitivity in variables](#understanding-case-sensitivity-in-variables)
- [Add two numbers with JavaScript](#add-two-numbers-with-javascript)
- [Subtract one number from another with JavaScript](#subtract-one-number-from-another-with-javascript)
- [Multiply two numbers with JavaScript](#subtract-two-numbers-with-javascript)
- [Divide one number by another with JavaScript](#divide-one-number-by-another-with-javascript)
- [Increment a number with JavaScript](#increment-a-number-with-javascript)
- [Decrement a number with JavaScript](#decrement-a-number-with-javascript)
- [Create decimal numbers with JavaScript](#create-decimal-numbers-with-javascript)
- [Multiply two decimals with JavaScript](#multiply-two-decimals-with-javascript)
- [Divide one decimal by another with JavaScript](#divide-one-decimal-by-another-with-javascript)
- [Finding a remainder in JavaScript](#finding-a-remainder-in-javascript)
- [Compound assignment with augmented addition](#compound-assignment-with-augmented-addition)
- [Compound assignment with augmented subtraction](#compound-assignment-with-augmented-subtraction)
- [Compound assignment with augmented multiplication](#compound-assignment-with-augmented-multiplication)
- [Compound assignment with augmented division](#compound-assignment-with-augmented-division)
- [Declare string variables](#declare-string-variables)
- [Escaping literal quotes in strings](#escaping-literal-quotes-in-strings)
- [Quoting strings with single quotes](#quoting-strings-with-single-quotes)
- [Escape sequences in strings](#escape-sequences-in-strings)
- [Concatenating strings with the plus operator](#concatenating-strings-with-the-plus-operator)
- [Constructing strings with variables](#constructing-strings-with-variables)
- [Appending variables to strings](#appending-variables-to-strings)
- [Find the length of a string](#find-the-length-of-a-string)
- [Use bracket notation to find the first character in a string](#use-bracket-notation-to-find-the-first-character-in-a-string)
- [Understand string immutability](#understand-string-immutability)
- [Use bracket notation to find the nth character in a string](#use-bracket-notation-to-find-the-nth-character-in-a-string)
- [Use bracket notation to find the last character in a string](#use-bracket-notation-to-find-the-last-character-in-a-string)
- [Use bracket notation to find the nth-to-last character in a string](#use-bracket-notation-to-find-the-nth-to-last-character-in-a-string)
- [Word blanks](#word-blanks)
- [Store multiple values in one variable using JavaScript arrays](#store-multiple-values-in-one-variable-using-javascript-arrays)
- [Nest one array within another array](#nest-one-array-within-another-array)
- [Access array data with indexes](#access-array-data-with-indexes)
- [Modify array data with indexes](#modify-array-data-with-indexes)
- [Access multi-dimensional arrays with indexes](#access-multi-dimensional-arrays-with-indexes)
- [Manipulate arrays with push()](#manipulate-arrays-with-push())
- [Manipulate arrays with pop()](#manipulate-arrays-with-pop())
- [Manipulate arrays with shift()](#manipulate-arrays-with-shift())
- [Manipulate arrays with unshift()](#manipulate-arrays-with-unshift())
- [Shopping list](#shopping-list)
- [Write reusable JavaScript with functions](#write-reusable-javascript-with-functions)
- [Passing values to functions with arguments](#passing-values-to-functions-with-arguments)
- [Global scope and functions](#global-scope-and-functions)
- [Local scope and functions](#local-scope-and-functions)
- [Global versus local scope in functions](#global-versus-local-scope-in-functions)
- [Return a value from a function with return](#return-a-value-from-a-function-with-return)
- [Understanding undefined value returned from a function](#understanding-undefined-value-returned-from-a-function)
- [Assignment with a returned value](#assignment-with-a-returned-value)
- [Stand in line](#stand-in-line)
- [Understanding boolean values](#understanding-boolean-values)
- [Use conditional logic with if statements](#use-conditional-logic-with-if-statements)
- [Comparison with the equality operator](#comparison-with-the-equality-operator)
- [Comparison with the strict equality operator](#comparison-with-the-strict-equality-operator)
- [Practice comparing different values](#practice-comparing-different-values)
- [Comparison with the inequality operator](#comparison-with-the-inequality-operator)
- [Comparison with the strict inequality operator](#comparison-with-the-strict-inequality-operator)
- [Comparison with the greater than operator](#comparison-with-the-greater-than-operator)
- [Comparison with the greater than or equal to operator](#comparison-with-the-greater-than-or-equal-to-operator)
- [Comparison with the less than operator](#comparison-with-the-less-than-operator)
- [Comparison with the less than or equal to operator](#comparison-with-the-less-than-or-equal-to-operator)
- [Comparison with the logical and operator](#comparison-with-the-logical-and-operator)
- [Comparison with the logical-or operator](#comparison-with-the-logical-or-operator)
- [Introducing else statements](#introducing-else-statements)
- [Introducing else if statements](#introducing-else-if-statements)
- [Logical order in if else statements](#logical-order-in-if-else-statements)
- [Chaining if else statements](#chaining-if-else-statements)
- [Golf code](#golf-code)
- [Selecting from many options with switch statements](#selecting-from-many-options-with-switch-statements)
- [Adding a default option in switch statement](#adding-a-default-option-in-switch-statement)
- [Multiple identical options in switch statement](#multiple-identical-options-in-switch-statement)
- [Replacing if else chains with switch](#replacing-if-else-chains-with-switch)
- [Returning boolean values from functions](#returning-boolean-values-from-functions)
- [Return early pattern for functions](#return-early-pattern-for-functions)
- [Counting cards](#counting-cards)
- [Build JavaScript objects](#build-javascript-objects)
- [Accessing object properties with dot notation](#accessing-object-properties-with-dot-notation)
- [Accessing object properties with bracket notation](#accessing-object-properties-with-bracket-notation)
- [Accessing object properties with variables](#accessing-object-properties-with-variables)
- [Updating object properties](#updating-object-properties)
- [Add new properties to a JavaScript object](#add-new-properties-to-a-javascript-object)
- [Delete properties from a JavaScript object](#delete-properties-from-a-javascript-object)
- [Using objects for lookups](#using-objects-for-lookups)
- [Testing objects for properties](#testing-objects-for-properties)
- [Manipulating complex objects](#manipulating-complex-objects)
- [Accessing nested objects](#accessing-nested-objects)
- [Accessing nested arrays](#accessing-nested-arrays)
- [Record collection](#record-collection)
- [Iterate with JavaScript while loops](#iterate-with-javascript-while-loops)
- [Iterate with JavaScript for loops](#iterate-with-javascript-for-loops)
- [Iterate odd numbers with a for loop](#iterate-odd-numbers-with-a-for-loop)
- [Count backwards with a for loop](#count-backwards-with-a-for-loop)
- [Iterate through an array with a for loop](#iterate-through-an-array-with-a-for-loop)
- [Nesting for loops](#nesting-for-loops)
- [Iterate with JavaScript do while loop](#iterate-with-javascript-do-while-loop)
- [Profile lookup](#profile-lookup)
- [Generate random fractions with JavaScript](#generate-random-fractions-with-javascript)
- [Generate random whole numbers with JavaScript](#generate-random-whole-numbers-with-JavaScript)
- [Generate random whole numbers within a range](#generate-random-whole-numbers-within-a-range)
- [Use the parseInt function](#use-the-parseint-function)
- [Use the parseInt function with a radix](#use-the-parseint-function-with-a-radix)
- [Use the conditional ternary operator](#use-the-conditional-ternary-operator)
- [Use multiple conditional ternary operators](#use-multiple-conditional-ternary-operators)

----

#### Comment your JavaScript code
Create an `inline` comment, and a `multi-line` comment.

````JavaScript
// This is an inline comment

/*
 This is a multi-line comment.
 This has been an excercise on writing comments in JavaScript.
*/
````
----

#### Declare JavaScript variables
`Variable` names can be made up of numbers, letters, and `$` or `_`, but may not contain spaces or start with a number.
Use the `var` keyword to create a variable called `myName`.

````JavaScript
// Example
var ourName;

// Declare myName below this name
var myName;
````
----

#### Storing values with the assignment operator
Assign the value `7` to variable `a`. Assign the contents of `a` to variable `b`.

````JavaScript
// Setup
var a;
var b = 2;

// Change code below this line
a = 7;
b = a;
````
----

#### Initializing variables with the assignment operator
Define a variable `a` with `var` and initialize it to a value of `9`.

````JavaScript
// Example
var ourVar = 19;

// Change code below this line
var a = 9;
````
----

#### Understanding uninitialized variables
Initialize the three variables `a`, `b`, and `c` with `5`, `10`, and `"I am a"` respectively so that they will not be `undefined`.

````JavaScript
// Initialize these three variables
var a = 5;
var b = 10;
var c = "I am a";

// Do not change code below this line
a = a + 1;
b = b + 5;
c = c + " String!";
````
----

#### Understanding case sensitivity in variables
Modify the existing declarations and assignments so their names use `camelCase`.
Do not create any new variables.

````JavaScript
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
````
----

#### Add two numbers with JavaScript
Change the `0` so that sum will equal `20`.

````JavaScript
// Add two numbers
var sum = 10 + 10;
````
----

#### Subtract one number from another with JavaScript
Change the `0` so the difference is `12`.

````JavaScript
// Subtract two numbers
var difference = 45 - 33;
````
----

#### Multiply two numbers with JavaScript
Change the `0` so that product will equal `80`.

````JavaScript
// Multiply two numbers
var product = 8 * 10;
````
----

#### Divide one number by another with JavaScript
Change the `0` so that quotient is equal to `2`.

````JavaScript
// Divide two numbers
var quotient = 66 / 33;
````
----

#### Increment a number with JavaScript
Change the code to use the `++` operator on `myVar`.

````JavaScript
var myVar = 87;

// Only change code below this line
myVar++;
````
----

#### Decrement a number with JavaScript
Change the code to use the `--` operator on `myVar`.

````JavaScript
var myVar = 11;

// Only change code below this line
myVar--;
````
----

#### Create decimal numbers with JavaScript
Create a variable `myDecimal` and give it a decimal value with a fractional part (e.g.` 5.7`).

````JavaScript
var ourDecimal = 5.7;

// Only change code below this line
var myDecimal = 4.4;
````
----

#### Multiply Two Decimals with JavaScript
Change the `0.0` so that product will equal `5.0`.

````JavaScript
// Decimal product
var product = 2.0 * 2.5;
````
----

#### Divide one decimal by another with JavaScript
Change the `0.0` so that quotient will equal to `2.2`.

````JavaScript
// Decimal quotient
var quotient = 4.4 / 2.0;
````
----
