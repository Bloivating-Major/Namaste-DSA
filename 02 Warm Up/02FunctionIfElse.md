# 📘 **Namaste DSA – Warm Up Module**

## **Class 02: Functions & If-Else**

> *By Akshay Saini*

---

## 🎯 **Focus of This Class**

In this class, we move one step closer to **real programming**.

You will learn:

* How to **reuse code**
* How to **make decisions in code**
* How to **combine logic with conditions**

This is where programming starts to feel powerful.

---

## 🧠 **What Are Functions?**

A **function** is:

> A block of code written once and used multiple times.

### Why We Need Functions

* Avoid repeating code
* Make programs readable
* Break big problems into small parts

---

## 🧩 **Key Properties of Functions**

A function:

* Is **created once**
* Can be **called any number of times**
* Can **return a value**

### Basic Function Syntax

```js
function greet() {
  console.log("Hello!");
}
```

Calling the function:

```js
greet();
```

---

## 🔁 **Functions With Input (Parameters)**

```js
function greet(name) {
  console.log("Hello " + name);
}

greet("Akshay");
```

* `name` is input
* Function behaves differently based on input

---

## ↩️ **Functions That Return a Value**

```js
function add(a, b) {
  return a + b;
}

const result = add(10, 20);
console.log(result);
```

> `return` sends output back to where the function was called.

---

## 🗳️ **Example 1: Check Voting Eligibility**

```js
function canVote(age) {
  if (age >= 18) {
    return "Eligible to vote";
  } else {
    return "Not eligible to vote";
  }
}

console.log(canVote(20));
console.log(canVote(15));
```

---

## 🔢 **Example 2: Check Even or Odd**

```js
function isEvenOrOdd(number) {
  if (number % 2 === 0) {
    return "Even";
  } else {
    return "Odd";
  }
}

console.log(isEvenOrOdd(10));
console.log(isEvenOrOdd(7));
```

---

## ⬛ **Example 3: Find Square of a Number**

```js
function square(num) {
  return num * num;
}

console.log(square(5));
```

---

## ➕ **Example 4: Find Sum of Two Numbers**

```js
function sum(a, b) {
  return a + b;
}

console.log(sum(3, 7));
```

---

## 🔀 **What Is If-Else?**

`if-else` is used to:

> Check whether a condition is true or false.

### Basic Syntax

```js
if (condition) {
  // runs if condition is true
} else {
  // runs if condition is false
}
```

---

## 🧠 **Why If-Else Is Important**

* Real programs need decisions
* Logic depends on conditions
* Almost every algorithm uses conditions

In this class:

* `if-else` is used **inside functions**
* To validate input
* To control output

---

## 🧠 **Key Takeaways**

* Functions help reuse code
* Write once, call many times
* Functions can take input and return output
* `if-else` helps make decisions
* Combining functions + if-else is core programming

---

## ✍️ **Practice Tasks (Must Do)**

* ✅ Write a function to check voting eligibility
* ✅ Write a function to check even or odd
* ✅ Write a function to find square
* ✅ Write a function to add two numbers
* ✍️ Try changing inputs and observe outputs

Practice here:
👉 [https://namastedev.com/playground](https://namastedev.com/playground)

---

✨ **Functions build structure.
Conditions build logic.
Together, they build programs.** 🚀
