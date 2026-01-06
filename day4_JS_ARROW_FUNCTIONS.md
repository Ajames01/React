# JavaScript Arrow Functions, Map, Filter, and Reduce

This document demonstrates the use of **arrow functions**, **map**, **filter**, and **reduce** in JavaScript with practical examples.

---

## 🚀 Arrow Functions

Arrow functions provide a concise way to write function expressions.  
Syntax: `(parameter) => expression`

### Example 1: Simple Arrow Function
```js
const hello = () => console.log("hello"); 
hello(); // Output: hello
```

### Example 2: Arrow Function with Parameters
```js
const hello = (name, age) => { //It takes in two parameters nameand age
    console.log(`hello ${name}`);
    console.log(`You are ${age}yrs old`);
    console.log(`You shouldn't waste your time`);
};

hello("Kelvin", 25);
// Output:
// hello Kelvin
// You are 25yrs old
// You shouldn't waste your time
```

---

## ⏱️ setTimeout Function

`setTimeout` accepts a callback and executes it after a given time (in milliseconds).

### Example 1: Passing a Function Reference
```js
function hello() {
    console.log("Hello");
}

setTimeout(hello, 3000); // Executes after 3 seconds
```

### Example 2: Using an Anonymous Function Expression
```js
setTimeout(function() {
    console.log("Hello");
}, 3000);
```

---

## 🔢 Map Method

The `map()` method creates a new array by applying a function to each element.

### Example: Squares of Numbers
```js
const numbers = [1, 2, 3, 4, 5, 6];
const squares = numbers.map((element) => Math.pow(element, 2));

console.log(squares); 
// Output: [1, 4, 9, 16, 25, 36]
```

### Example: Cubes of Numbers
```js
const numbers = [1, 2, 3, 4, 5, 6];
const cubes = numbers.map((element) => Math.pow(element, 3));

console.log(cubes); 
// Output: [1, 8, 27, 64, 125, 216]
```

---

## 🔍 Filter Method

The `filter()` method creates a new array with elements that pass a test.

### Example: Even Numbers
```js
const evenNums = numbers.filter((element) => element % 2 === 0);
console.log(evenNums); 
// Output: [2, 4, 6]
```

### Example: Odd Numbers
```js
const oddNums = numbers.filter((element) => element % 2 !== 0);
console.log(oddNums); 
// Output: [1, 3, 5]
```

---

## ➕ Reduce Method

The `reduce()` method applies a function against an accumulator and each element to reduce the array to a single value.

### Example: Sum of All Numbers
```js
const total = numbers.reduce((accumulator, element) => accumulator + element);

console.log(total); 
// Output: 21
```

---

## 📝 Notes
- `===` is the **strict equality operator** in JavaScript. It checks both value and type without type conversion.
- Arrow functions are best for short, one‑time use functions.
- `map`, `filter`, and `reduce` are powerful array methods for transformation, selection, and aggregation.

