# 🧍 JavaScript Objects

An **object** is a collection of **related properties and methods (functions)** used to represent real-life things such as **people, products, or places**.

```js
objects = { key: value, method: function() {} }
```

* **Properties** → describe the object
* **Methods** → actions the object can perform
* A **method** is simply a function that belongs to an object

---

## 🧩 Creating an Object

```js
const person1 = {
  firstName: "Spongebob", // properties are key-value pairs
  lastName: "Squarepants",
  age: 30,
  isEmployed: true,
  sayHello: function () {
    console.log("Hi, I'm Spongebob");
  }
};
```

---

## ▶️ Accessing Object Properties

```js
console.log(person1.firstName);
console.log(person1.lastName);
console.log(person1.age);
console.log(person1.isEmployed);
```

---

## ⚙️ Calling Object Methods

```js
person1.sayHello();
```

---

## ➕ Adding Multiple Methods

Objects can have **more than one method**.

```js
const person1 = {
  firstName: "Spongebob",
  lastName: "Squarepants",
  age: 30,
  isEmployed: true,
  sayHello: function () {
    console.log("Hi, I'm Spongebob");
  },
  eat: function () {
    console.log("I am eating a Krabby Patty");
  }
};

person1.sayHello();
person1.eat();
```

⚠️ **Important:**
Each property or method **must be separated by a comma**.

---

## 👥 Creating Multiple Objects

Each object must have a **unique variable name**.

```js
const person2 = {
  firstName: "Patrick",
  lastName: "Star",
  age: 42,
  isEmployed: false,
  sayHello: function () {
    console.log("Hey, I'm Patrick...");
  },
  eat: function () {
    console.log("I am eating roast beef, chicken, and pizza");
  }
};
```

---

## 🔎 Accessing Another Object

```js
console.log(person2.firstName);
console.log(person2.lastName);
console.log(person2.age);
console.log(person2.isEmployed);

person2.sayHello();
person2.eat();
```

---

## 📝 Key Notes

* Objects use **curly braces `{}`**
* Properties use **key: value** pairs
* Methods are **functions inside objects**
* Always separate properties with **commas**
* Object properties are accessed using **dot notation**


