1) Difference between var, let and const

**var**  old system, function scope. Same variable can be declared again.  
**let**  block scope, cannot be declared again, but value can be changed.  
**const** block scope, once value is set it cannot be changed.  

Example:  
```js
var name = "Amit";
var name = "Das"; 

let age = 21;
age = 22; 

const country = "Bangladesh";




**************************

  2) map(), forEach(), filter()

map() gives a new array.
forEach() runs a loop, does not return anything.
filter() checks condition and gives a new array.

Example:

let numbers = [1,2,3,4];

let double = numbers.map(n => n * 2);

numbers.forEach(n => console.log(n)); 

let even = numbers.filter(n => n % 2 === 0); 


*************************************


3) Arrow function

In ES6, arrow function is used to write functions in an easy way.
It is short and clean.

Example:

function greet() {
  return "Hello, I am Amit Das";
}

const greet2 = () => "Hello, I am Amit Das";


*************************************

4) Destructuring assignment

With destructuring, we can take values from array or object into variables easily.

Example with array:

let arr = ["Amit", 21];
let [name, age] = arr;

console.log(name); 
console.log(age);  


Example with object:

let person = { name: "Amit Das", age: 21 };
let { name, age } = person;

console.log(name); 
console.log(age);  


*************************************

5) Template literals

Template literals are written using backticks `.
We can use variables inside string using ${ }.
It is easier than using plus (+) for concatenation.

Example:

let name = "Amit";
let age = 21;

let text1 = "My name is " + name + " and I am " + age + " years old.";
let text2 = `My name is ${name} and I am ${age} years old.`;

console.log(text1);
console.log(text2);

*************************************