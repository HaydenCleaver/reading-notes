# Class 8 Reading Notes

## Expressions and Operators

Java script ahs binary and unary operators, and one ternary operator (the conditional operator?)

Binary operators require one operand before the operator and one after.

`3 + 4` or `x*y`

A unary operator only requires one operand, before or after.

`x++` or `++x`

***

### Assignment Operators

Assignment operators assign a value to the left operand based upon the value of the right one. 

`x = f()` or `x *= f()`

#### Assigning to Properties

If a variable refers to an object, the left side of an assignment expression may be used to assign values to the properties of that variable.

```
let obj = {};

obj.x = 3;

console.log(obj.x); // Prints 3.

console.log(obj); // Prints { x: 3 }.
```

#### Destructuring

Destructuring assignment syntax makes it possible to extract data from arrays or objects.

#### Evaluation and Nesting

Variables can be chained / nested within each other to evaluate.  However trying to declare multiple variables like that doesn't work / isn't recommended.

### Comparison Operators

These are used to compare two or more operators to each other and returns a true or false value based upon the answer.

`x == y` or `x && y` and etc...

***

[Link to Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

***

## For and While Loops

Loops are a way to effeciently run a piece of code multiple times.

### For Loops

For loops repeat a sequence of code until a specific condition has been met.  Until it is met, an increment counter of some kind will update.

### While Loops

While loops repeat their code *unless* a specific condition has been met.
 
***

[Return to Table of Contents](https://haydencleaver.github.io/reading-notes/)