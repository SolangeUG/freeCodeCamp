## Basic JavaScript

> JavaScript is a high-level programming language that all modern web browsers support.
It is also one of the core technologies of the web, along with HTML and CSS that you may have learned previously.
This section will cover basic JavaScript programming concepts, which range from variables and arithmetic to objects and loops.

- [Comment your JavaScript code][1]
- [Declare JavaScript variables][2]
- [Storing values with the assignment operator][3]
- [Initializing variables with the assignment operator][4]
- [Understanding uninitialized variables][5]
- [Understanding case sensitivity in variables][6]
- [Add two numbers with JavaScript][7]
- [Subtract one number from another with JavaScript][8]
- [Multiply two numbers with JavaScript][9]
- [Divide one number by another with JavaScript][10]
- [Increment a number with JavaScript][11]
- [Decrement a number with JavaScript][12]
- [Create decimal numbers with JavaScript][13]
- [Multiply two decimals with JavaScript][14]
- [Divide one decimal by another with JavaScript][15]
- [Finding a remainder in JavaScript][16]
- [Compound assignment with augmented addition][17]
- [Compound assignment with augmented subtraction][18]
- [Compound assignment with augmented multiplication][19]
- [Compound assignment with augmented division][20]
- [Declare string variables][21]
- [Escaping literal quotes in strings][22]
- [Quoting strings with single quotes][23]
- [Escape sequences in strings][24]
- [Concatenating strings with the plus operator][25]
- [Constructing strings with variables][26]
- [Appending variables to strings][27]
- [Find the length of a string][28]
- [Use bracket notation to find the first character in a string][29]
- [Understand string immutability][30]
- [Use bracket notation to find the nth character in a string][31]
- [Use bracket notation to find the last character in a string][32]
- [Use bracket notation to find the nth-to-last character in a string][33]
- [Word blanks][34]
- [Store multiple values in one variable using JavaScript arrays][35]
- [Nest one array within another array][36]
- [Access array data with indexes][37]
- [Modify array data with indexes][38]
- [Access multi-dimensional arrays with indexes][39]
- [Manipulate arrays with push()][40]
- [Manipulate arrays with pop()][41]
- [Manipulate arrays with shift()][42]
- [Manipulate arrays with unshift()][43]
- [Shopping list][44]
- [Write reusable JavaScript with functions][45]
- [Passing values to functions with arguments][46]
- [Global scope and functions][47]
- [Local scope and functions][48]
- [Global versus local scope in functions][49]
- [Return a value from a function with return][50]
- [Understanding undefined value returned from a function][51]
- [Assignment with a returned value][52]
- [Stand in line][53]
- [Understanding boolean values][54]
- [Use conditional logic with if statements][55]
- [Comparison with the equality operator][56]
- [Comparison with the strict equality operator][57]
- [Practice comparing different values][58]
- [Comparison with the inequality operator][59]
- [Comparison with the strict inequality operator][60]
- [Comparison with the greater than operator][61]
- [Comparison with the greater than or equal to operator][62]
- [Comparison with the less than operator][63]
- [Comparison with the less than or equal to operator][64]
- [Comparison with the logical and operator][65]
- [Comparison with the logical-or operator][66]
- [Introducing else statements][67]
- [Introducing else if statements][68]
- [Logical order in if else statements][69]
- [Chaining if else statements][70]
- [Golf code][71]
- [Selecting from many options with switch statements][72]
- [Adding a default option in switch statement][73]
- [Multiple identical options in switch statement][74]
- [Replacing if else chains with switch][75]
- [Returning boolean values from functions][76]
- [Return early pattern for functions][77]
- [Counting cards][78]
- [Build JavaScript objects][79]
- [Accessing object properties with dot notation][80]
- [Accessing object properties with bracket notation][81]
- [Accessing object properties with variables][82]
- [Updating object properties][83]
- [Add new properties to a JavaScript object][84]
- [Delete properties from a JavaScript object][85]
- [Using objects for lookups][86]
- [Testing objects for properties][87]
- [Manipulating complex objects][88]
- [Accessing nested objects][89]
- [Accessing nested arrays][90]
- [Record collection][91]
- [Iterate with JavaScript while loops][92]
- [Iterate with JavaScript for loops][93]
- [Iterate odd numbers with a for loop][94]
- [Count backwards with a for loop][95]
- [Iterate through an array with a for loop][96]
- [Nesting for loops][97]
- [Iterate with JavaScript do while loop][98]
- [Profile lookup][99]
- [Generate random fractions with JavaScript][100]
- [Generate random whole numbers with JavaScript][101]
- [Generate random whole numbers within a range][102]
- [Use the parseInt function][103]
- [Use the parseInt function with a radix][104]
- [Use the conditional ternary operator][105]
- [Use multiple conditional ternary operators][106]

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

#### Increment a number with JavaScript

---

#### Decrement a number with JavaScript

---

#### Create decimal numbers with JavaScript

---

#### Multiply two decimals with JavaScript

---

#### Divide one decimal by another with JavaScript

---

#### Finding a remainder in JavaScript

---

#### Compound assignment with augmented addition

---

#### Compound assignment with augmented subtraction

---

#### Compound assignment with augmented multiplication

---

#### Compound assignment with augmented division

---

#### Declare string variables

---

#### Escaping literal quotes in strings

---

#### Quoting strings with single quotes

---

#### Escape sequences in strings

---

#### Concatenating strings with the plus operator

---

#### Constructing strings with variables

---

#### Appending variables to strings

---

#### Find the length of a string

---

#### Use bracket notation to find the first character in a string

---

#### Understand string immutability

---

#### Use bracket notation to find the nth character in a string

---

#### Use bracket notation to find the last character in a string

---

#### Use bracket notation to find the nth-to-last character in a string

---

#### Word blanks

---

#### Store multiple values in one variable using JavaScript arrays

---

#### Nest one array within another array

---

#### Access array data with indexes

---

#### Modify array data with indexes

---

#### Access multi-dimensional arrays with indexes

---

#### Manipulate arrays with push()

---

#### Manipulate arrays with pop()

---

#### Manipulate arrays with shift()

---

#### Manipulate arrays with unshift()

---

#### Shopping list

---

#### Write reusable JavaScript with functions

---

#### Passing values to functions with arguments

---

#### Global scope and functions

---

#### Local scope and functions

---

#### Global versus local scope in functions

---

#### Return a value from a function with return

---

#### Understanding undefined value returned from a function

---

#### Assignment with a returned value

---

#### Stand in line

---

#### Understanding boolean values

---

#### Use conditional logic with if statements

---

#### Comparison with the equality operator

---

#### Comparison with the strict equality operator

---
#### Practice comparing different values


---

#### Comparison with the inequality operator

---

#### Comparison with the strict inequality operator

---

#### Comparison with the greater than operator

---

#### Comparison with the greater than or equal to operator

---

#### Comparison with the less than operator

---

#### Comparison with the less than or equal to operator

---

#### Comparison with the logical and operator

---

#### Comparison with the logical or operator

---

#### Introducing else statements

---

#### Introducing else if statements

---

#### Logical order in if else statements

---

#### Chaining if else statements

---

#### Golf code

---

#### Selecting from many options with switch statements

---

#### Adding a default option in switch statement

---

#### Multiple identical options in switch statement

---

#### Replacing if else chains with switch

---

#### Returning boolean values from functions

---

#### Return early pattern for functions

---

#### Counting cards

---

#### Build JavaScript objects

---

#### Accessing object properties with dot notation

---

#### Accessing object properties with bracket notation

---

#### Accessing object properties with variables

---

#### Updating object properties

---

#### Add new properties to a JavaScript object

---

#### Delete properties from a JavaScript object

---

#### Using objects for lookups

---

#### Testing objects for properties

---

#### Manipulating complex objects

---

#### Accessing nested objects

---

#### Accessing nested arrays

---

#### Record collection

---

#### Iterate with JavaScript while loops

---

#### Iterate with JavaScript for loops

---

#### Iterate odd numbers with a for loop

---

#### Count backwards with a for loop

---

#### Iterate through an array with a for loop

---

#### Nesting for loops

---

#### Iterate with JavaScript do while loop

---

#### Profile lookup

---

#### Generate random fractions with JavaScript

---

#### Generate random whole numbers with JavaScript

---

#### Generate random whole numbers within a range

---

#### Use the parseInt function

---

#### Use the parseInt function with a radix

---

#### Use the conditional ternary operator

---

#### Use multiple conditional ternary operators

---


[1]: #comment-your-javascript-code
[2]: #declare-javascript-variables
[3]: #storing-values-with-the-assignment-operator
[4]: #initializing-variables-with-the-assignment-operator
[5]: #understanding-uninitialized-variables
[6]: #understanding-case-sensitivity-in-variables
[7]: #add-two-numbers-with-javascript
[8]: #subtract-one-number-from-another-with-javascript
[9]: #subtract-two-numbers-with-javascript
[10]: #divide-one-number-by-another-with-javascript
[11]: #increment-a-number-with-javascript
[12]: #decrement-a-number-with-javascript
[13]: #create-decimal-numbers-with-javascript
[14]: #multiply-two-decimals-with-javascript
[15]: #divide-one-decimal-by-another-with-javascript
[16]: #finding-a-remainder-in-javascript
[17]: #compound-assignment-with-augmented-addition
[18]: #compound-assignment-with-augmented-subtraction
[19]: #compound-assignment-with-augmented-multiplication
[20]: #compound-assignment-with-augmented-division
[21]: #declare-string-variables
[22]: #escaping-literal-quotes-in-strings
[23]: #quoting-strings-with-single-quotes
[24]: #escape-sequences-in-strings
[25]: #concatenating-strings-with-the-plus-operator
[26]: #constructing-strings-with-variables
[27]: #appending-variables-to-strings
[28]: #find-the-length-of-a-string
[29]: #use-bracket-notation-to-find-the-first-character-in-a-string
[30]: #understand-string-immutability
[31]: #use-bracket-notation-to-find-the-nth-character-in-a-string
[32]: #use-bracket-notation-to-find-the-last-character-in-a-string
[33]: #use-bracket-notation-to-find-the-nth-to-last-character-in-a-string
[34]: #word-blanks
[35]: #store-multiple-values-in-one-variable-using-javascript-arrays
[36]: #nest-one-array-within-another-array
[37]: #access-array-data-with-indexes
[38]: #modify-array-data-with-indexes
[39]: #access-multi-dimensional-arrays-with-indexes
[40]: #manipulate-arrays-with-push()
[41]: #manipulate-arrays-with-pop()
[42]: #manipulate-arrays-with-shift()
[43]: #manipulate-arrays-with-unshift()
[44]: #shopping-list
[45]: #write-reusable-javascript-with-functions
[46]: #passing-values-to-functions-with-arguments
[47]: #global-scope-and-functions
[48]: #local-scope-and-functions
[49]: #global-versus-local-scope-in-functions
[50]: #return-a-value-from-a-function-with-return
[51]: #understanding-undefined-value-returned-from-a-function
[52]: #assignment-with-a-returned-value
[53]: #stand-in-line
[54]: #understanding-boolean-values
[55]: #use-conditional-logic-with-if-statements
[56]: #comparison-with-the-equality-operator
[57]: #comparison-with-the-strict-equality-operator
[58]: #practice-comparing-different-values
[59]: #comparison-with-the-inequality-operator
[60]: #comparison-with-the-strict-inequality-operator
[61]: #comparison-with-the-greater-than-operator
[62]: #comparison-with-the-greater-than-or-equal-to-operator
[63]: #comparison-with-the-less-than-operator
[64]: #comparison-with-the-less-than-or-equal-to-operator
[65]: #comparison-with-the-logical-and-operator
[66]: #comparison-with-the-logical-or-operator
[67]: #introducing-else-statements
[68]: #introducing-else-if-statements
[69]: #logical-order-in-if-else-statements
[70]: #chaining-if-else-statements
[71]: #golf-code
[72]: #selecting-from-many-options-with-switch-statements
[73]: #adding-a-default-option-in-switch-statement
[74]: #multiple-identical-options-in-switch-statement
[75]: #replacing-if-else-chains-with-switch
[76]: #returning-boolean-values-from-functions
[77]: #return-early-pattern-for-functions
[78]: #counting-cards
[79]: #build-javascript-objects
[80]: #accessing-object-properties-with-dot-notation
[81]: #accessing-object-properties-with-bracket-notation
[82]: #accessing-object-properties-with-variables
[83]: #updating-object-properties
[84]: #add-new-properties-to-a-javascript-object
[85]: #delete-properties-from-a-javascript-object
[86]: #using-objects-for-lookups
[87]: #testing-objects-for-properties
[88]: #manipulating-complex-objects
[89]: #accessing-nested-objects
[90]: #accessing-nested-arrays
[91]: #record-collection
[92]: #iterate-with-javascript-while-loops
[93]: #iterate-with-javascript-for-loops
[94]: #iterate-odd-numbers-with-a-for-loop
[95]: #count-backwards-with-a-for-loop
[96]: #iterate-through-an-array-with-a-for-loop
[97]: #nesting-for-loops
[98]: #iterate-with-javascript-do-while-loop
[99]: #profile-lookup
[100]: #generate-random-fractions-with-javascript
[101]: #generate-random-whole-numbers-with-javascript
[102]: #generate-random-whole-numbers-within-a-range
[103]: #use-the-parseint-function
[104]: #use-the-parseint-function-with-a-radix
[105]: #use-the-conditional-ternary-operator
[106]: #use-multiple-conditional-ternary-operators
