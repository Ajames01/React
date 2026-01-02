# 📦 JavaScript Arrays

An **array** is a variable-like structure that can store **multiple values** in a single variable.

---

## 🧩 Creating an Array

```js
let fruits = ["apple", "orange", "banana"];
console.log(fruits);
```

---

## 🔢 Array Indexing

* JavaScript arrays **start at index 0**
* Each element is accessed using its index

```js
console.log(fruits[0]); // apple
console.log(fruits[1]); // orange
console.log(fruits[2]); // banana
```

---

## ✏️ Modifying Array Elements

You can change an element by accessing its index.

```js
fruits[1] = "watermelon";

console.log(fruits[0]); // apple
console.log(fruits[1]); // watermelon
console.log(fruits[2]); // banana
```

---

## ➕ Adding & ➖ Removing Elements

### Add to the end (`push`)

```js
fruits.push("coconut");
```

### Remove from the end (`pop`)

```js
fruits.pop();
```

### Add to the beginning (`unshift`)

```js
fruits.unshift("mango");
```

### Remove from the beginning (`shift`)

```js
fruits.shift();
```

---

## 📏 Array Length

```js
console.log(fruits.length); // number of elements in the array
```

---

## 🔍 Finding an Element Index

```js
let index = fruits.indexOf("apple");
console.log(index);
```

* Returns `-1` if the element is **not found**
* Useful in `if` statements

---

## 🔁 Looping Through an Array

### Using a `for` loop

```js
for (let i = 0; i < fruits.length; i++) {
  console.log(fruits[i]);
}
```

### Using a `for...of` loop (simpler)

```js
for (let fruit of fruits) {
  console.log(fruit);
}
```

---

## 🔤 Sorting an Array

### Alphabetical order

```js
fruits.sort();
```

### Reverse order

```js
fruits.sort().reverse();
```

---

## ✅ Key Notes

* Arrays start at **index 0**
* `length` gives the total number of elements
* `indexOf()` returns `-1` if the item doesn’t exist
* `for...of` is the easiest way to loop through arrays

---
