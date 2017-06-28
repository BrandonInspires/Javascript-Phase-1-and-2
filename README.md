# Javascript-Phase-1-and-2

# Phase 1
- [ ] Can describe what a variable is
```bash

```
- [ ] Can describe the difference between a local and global variable
```bash

```
- [ ] Can describe a Function
```bash

```
- [ ] Can describe a Hash
```bash

```
- [ ] Can describe a Array
```bash

```
- [ ] Can describe a Set
```bash

```
- [ ] Can describe the ! (bang) operator
```bash

```
- [ ] Can describe an "if statement"
```bash

```
- [ ] Can describe a pure vs. impure function
```bash

```
- [ ] Can describe operator precedence
```bash

```
- [ ] Can describe the push Array method
```bash

```
- [ ] Can describe the pop Array method
```bash

```
- [ ] Can describe the shift Array method
```bash

```
- [ ] Can describe the unshift Array method
```bash

```
- [ ] Can describe the each Array method
```bash

```
- [ ] Can describe the map Array method
```bash

```
- [ ] Can describe the filter Array method
```bash

```
- [ ] Can describe the reduce Array method
```bash

```
- [ ] Can describe a closure
```bash

```
- [ ] Can write a Function in JavaScript
```bash

```
- [ ] Can write an Object literal in JavaScript
```bash

```
- [ ] Can write an Array literal in JavaScript
```bash

```
- [ ] Can write an String literal in JavaScript
```bash

```
- [ ] Can write an Number literal in JavaScript
```bash

```
- [ ] Can write and if/else statement in JavaScript
```bash

```
- [ ] Can write and switch statement in JavaScript
```bash

```
- [ ] Can write and while loop in JavaScript
```bash

```
- [ ] Can write and for loop in JavaScript
```bash

```
- [ ] Can write a pure function in JavaScript
```bash

```
- [ ] Can set the value of a property on a JavaScript Object using . syntax
```bash

```
- [ ] Can set the value of a property on a JavaScript Object using [] syntax
```bash

```
- [ ] Can get the value of a property on a JavaScript Object using . syntax
```bash

```
- [ ] Can get the value of a property on a JavaScript Object using [] syntax
```bash

```
- [ ] Can describe the difference between == and === in JavaScript
```bash

```
- [ ] Can describe the difference between var, let, and const in JavaScript
```bash

```
- [ ] Can use Array#push in JavaScript
```es6
> [1, 2, 3].push(4) // [1, 2, 3, 4]
4

> let arr = [1, 5, 10]
undefined

> arr.push(15)
15

> arr
[1, 5, 10, 15]
```
- [ ] Can use Array#pop in JavaScript
```es6
> let arr = [1, 3, 5]
undefined

> arr.pop()
5

> arr
[1, 3]
```
- [ ] Can use Array#shift in JavaScript
```es6
[1, 2, 3].shift() // returns 1
```
- [ ] Can use Array#unshift in JavaScript
```es6
[1, 2, 3].unshift(0) // returns [0, 1, 2, 3]
```
- [ ] Can use Array#forEach in JavaScript
```bash

```
- [ ] Can use Array#map in JavaScript
```bash

```
- [ ] Can use Array#filter in JavaScript
```bash

```
- [ ] Can use Array#reduce in JavaScript
```bash

```
- [ ] Can declare local vs. global variables in JavaScript
```bash

```
- [ ] Can get all the keys on a JavaScript object
```bash

```
- [ ] Can get all the values on a JavaScript object
```bash

```
- [ ] Can write a closure in JavaScript
```bash

```
- [ ] Can pass multiple objects into a function using a plain object as a single argument, in 
```bash

```
- [ ] Can describe lexical scope inheritance in JavaScript
```bash

```
- [ ] Can split a string into an array in JavaScript
```es6

```
- [ ] Can join an array into a string in JavaScript
```es6
[1, 2, 3].toString() // returns "1,2,3"

[1, 2, [[3, [[4]], [[5]]], [6]]].toString(); // returns "1,2,3,4,5,6" -- Flattens out the array
```
# Phase 2
- [ ] Can describe JavaScript hoisting
```bash

```
- [ ] Can write an immediately invoked function expression in JavaScript
```bash
( function(a, b) {return a + b} )();
```
- [ ] Can describe why immediately invoked function expressions are useful in JavaScript
```bash

```
- [ ] Can define a JavaScript Constructor
```bash

```
- [ ] Can add properties to the prototype of a JavaScript Constructor
```bash

```
- [ ] Can describe what a closure is
```bash

```
- [ ] Can give an example of when one might use a closures
```bash

```
- [ ] Can describe what the this operator is in JavaScript
```bash

```
- [ ] Can show at least three ways to declare what this will be when calling a function in JavaScript
```bash

```
- [ ] Can describe what a "higher order function" is in JavaScript
```bash
 A function that takes functions as arguments and returns functions
```
- [ ] Can write and example of a "higher order function" is in JavaScript
```bash

```
- [ ] Can describe the differences between bind, call, apply in JavaScript
```es6
var bound =  myFunction.bind(obj) // Bind creates a new function called bound with Myfunction as a method on obj

// Call temporaraly attaches a method to an object and runs it
customMethod.call(obj, 22) // call
customMethod.apply(obj, arr)
Apply does what call does and also attaches an externally scoped variable as the function's arguement
```
- [ ] Can describe what a pure JavaScript function is

 A pure function:
 1. Must take arguments
 1. Does not mutate state outside of its scope
 1. Given the same inputs will always produce the same output
 1. Does not produce [side effects](https://en.wikipedia.org/wiki/Side_effect_%28computer_science%29)
 1. Cannot call impure functions

 ```javascript
 let myVar = 5
 function doubleNumber(){ // impure function - relies on variable in the parent scope
  return myVar * 2
 }
 vs
 function pureDoubleNumber(5){ // pure function
  return arg1 * 2
 }
```


Exercises
- [ ] Complete the Object Oriented course on TeamTreeHouse
- [ ] Complete the Object Oriented exercises on FreeCodeCamp
- [ ] TodoList
