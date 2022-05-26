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

Destructuring assignment syntax makes it possible to extract data from arrays or objects. It mirrors 