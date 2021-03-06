# Javascript-Phase-1-and-2

# Phase 1
- [ ] Can describe what a variable is
```es6
 A variable is a placeholder for a value stored in a particular memory location
```
- [ ] Can describe the difference between a local and global variable
```es6
var globalVar = 10
var myFunction = function (){
	var localVar = 20
}
// A local variable is only accessable within its lexical scope
```
- [ ] Can describe a Function
```es6
function (parameters) {
	expression = do something + parameters
}
```
- [ ] Can describe a Hash
```bash

```
- [ ] Can describe a Array
```bash
  An ordered list - ex. [1, 2, 3]
```
- [ ] Can describe a Set
```bash
 An object that stores unique values of any type (primative or reference)
```
- [ ] Can describe the ! (bang) operator
```bash

```
- [ ] Can describe an "if statement"
```es6
 if (condition) {expression} else {expression}
```
- [ ] Can describe a pure vs. impure function
```bash
A pure function does not reference or mutate objects or variables outside of its scope.
Given the same input will always return the same value.
```
- [ ] Can describe operator precedence
```bash

```
- [ ] Can describe the push Array method
```bash
 [1,2,3,4].push(5) // [1,2,3,4,5] // adds an element to the end of an array
```
- [ ] Can describe the pop Array method
```es6
[1,2,3,4].pop() // [1,2,3] takes an element off the back of the array
```
- [ ] Can describe the shift Array method
```es6
[1,2,3,4].shift() // returns [2,3,4] // removes an element from the beginning of the array
```
- [ ] Can describe the unshift Array method
```es6
[2,3,4].unshift(0, 1) // returns [0,1,2,3,4]
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
A closure is a function that references or mutates variables outside of its own scope.
```
- [ ] Can write a Function in JavaScript
```es6
function FunctionName(parameters){ //Do Something }
```
- [ ] Can write an Object literal in JavaScript
```bash
var myObject = {"Name": "Brandon", "Age": 34}
```
- [ ] Can write an Array literal in JavaScript
```bash
 var myArray = [1,2,3,4]
```
- [ ] Can write an String literal in JavaScript
```bash
var myString = "Hello, this is a string"
```
- [ ] Can write an Number literal in JavaScript
```bash
var x = 5;
```
- [ ] Can write an if/else statement in JavaScript
```es6
function isNumber(parameter) {
	if (typeof(parameter) == "Number") {
	return 'The argument is a number'
	} else {
		return 'The argument is not a number'
	}
}

```
- [ ] Can write a switch statement in JavaScript
```es6
function FizzBuzz(){
var arr = 
	switch (true) {
	case num % 3 == 0 && num % 5 == 0:
	console.log('Fizz');
	break;
	case num % 3 == 0:
	console.log('Buzz')
	break;
	default:
	console.log(num)
	break;
	}
}
```
- [ ] Can write a while loop in JavaScript
```bash

```
- [ ] Can write a for loop in JavaScript
```es6
for (i = 0; i > 101; i++) {
	console.log(i)
}
```
- [ ] Can write a pure function in JavaScript
```bash

```
- [ ] Can set the value of a property on a JavaScript Object using . syntax
```es6
var myObj = {}; myObj.name = "Brandon" 
myObj // returns Object { name: "Brandon" }
```
- [ ] Can set the value of a property on a JavaScript Object using [] syntax
```es6
var myObj = {}; myObj["name"] = "George" // key must be in quotations
myObj // returns Object { name: "George" }
```
- [ ] Can get the value of a property on a JavaScript Object using . syntax
```es6
myObj.name
```
- [ ] Can get the value of a property on a JavaScript Object using [] syntax
```es6
myObj["name"] // must use quotes
```
- [ ] Can describe the difference between == and === in JavaScript
```es6
const x = 12
console.log(x === '12') // False - Triple Equal checks for type
console.log(x === 12) // True
console.log(x == 12) // True - Double Equal DOES NOT check for type and will do type coercion
console.log(x == '12') // True
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
```es6
let gVar = 5 // global variable

let myfunction = function(){
 let lVar = 10 // local variable
 }

```
- [ ] Can get all the keys on a JavaScript object
```bash
Object.keys(obj) // returns an array of enumerable keys
Object.getOwnPropertyNames(obj)// returns an array of all keys
```
- [ ] Can get all the values on a JavaScript object
```bash
 Object.values(obj) // returns an array of values
```
- [ ] Can write a closure in JavaScript
```es6
var myFunction = function(){
	var i = 0;
	return function closureFunction()
	{i++; console.log (i)};
}
```
- [ ] Can pass multiple objects into a function using a plain object as a single argument, in 
```es6
var array = [1, 2, 3, 4, 5]
function addOne(num) { return num + 1 }
addOne(...array)
```
- [ ] Can describe lexical scope inheritance in JavaScript
```bash

```
- [ ] Can split a string into an array in JavaScript
```es6
 "1,2,3,4,5,6".split(',') // returns ["1", "2", "3", "4", "5", "6"]
```
- [ ] Can join an array into a string in JavaScript
```es6
[1, 2, 3].toString() // returns "1,2,3"

[1, 2, [[3, [[4]], [[5]]], [6]]].toString(); // returns "1,2,3,4,5,6" -- Flattens out the array
```
# Phase 2
- [ ] Can describe JavaScript hoisting
```es6	
In a js file, variables are loaded into memory before code is run so that variables can be called before they are declared
```
- [ ] Can write an immediately invoked function expression in JavaScript
```bash
( function(a, b) {return a + b} )();
```
- [ ] Can describe why immediately invoked function expressions are useful in JavaScript
```bash
It's useful for running some function or performing some task once and throwing it away. It's useful for not polluting the global scope and for maintaining privacy.
```
- [ ] Can define a JavaScript Constructor
```bash
A Javascript Constructor is a special method for instantiating an object from a class.
A special object used to create and initialize objects based on its properties
```
- [ ] Can add properties to the prototype of a JavaScript Constructor
```es6
function MyConstructor (argument1, argument2){
	this.argument1 = argument1;
	this.argument2 = argument2;
}

MyConstructor.prototype.sum = function() {
	this.argument1 + this.argument2
}
MyConstructor.prototype.otherValue = 10
```
- [ ] Can describe what a closure is
```bash
 A closure is a function that references variables in its parent scope(s).
```
- [ ] Can give an example of when one might use a closures
```bash
function add(){
	todoList = []
	changelog = []
	changelog.push(new Date)
	return function (todo) {
	todoList.push(todo)
	changelog.push(new Date)
	}
}
// function creates a semi-hidden time log and time entry when functions are called.
var addTodo = (function add(){
	todoList = []
	changelog = []
	changelog.push("created new todo list:" + new Date)
	return function (todo) {
	todoList.push(todo)
	changelog.push("add: " + new Date)
	}
})()



var addTodo = add()
```
- [ ] Can describe what the this operator is in JavaScript
```es6	
"this" when used inside a function is the object that owns the function. 
When used inside an object it refers to the object itself
When used on a constructor it will refer to the specific instance 
```
- [ ] Can show at least three ways to declare what this will be when calling a function in JavaScript
```es6
myConstructor(name, age){
	this.name = name;
	this.age = age;
}

function(){
	this
}


```
- [ ] Can describe what a "higher order function" is in JavaScript
```es6
 A function that takes functions as arguments and returns functions
```
- [ ] Can write and example of a "higher order function" is in JavaScript
```es6
function add(x) {
	return function (y){return x + y}
}
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
