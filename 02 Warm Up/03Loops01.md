# 📘 **Namaste DSA – Warm Up Module**

## **Class 03: Loops (Part 01)**

> *By Akshay Saini*

---

## 🎯 **Focus of This Class**

In this class, we learn how to:

* Repeat work automatically
* Avoid writing the same code again and again
* Process multiple values efficiently

This is where **automation in programming** begins.

---

## 🔁 **What Is a Loop?**

A **loop** is:

> A way to run the same piece of code multiple times.

Instead of writing:

```js
console.log(1);
console.log(2);
console.log(3);
```

We use a loop.

> Loops run in a **cycle** until a condition becomes false.

---

## 🔂 **For Loop (Loop We Will Learn First)**

In Namaste DSA, we start with the **for loop**.

### For Loop Has 3 Parts:

1️⃣ **Initialization** – starting point
2️⃣ **Condition** – when to stop
3️⃣ **Incrementation** – how to move forward

---

### Basic For Loop Syntax

```js
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

Explanation:

* `let i = 0` → start
* `i < 5` → stop condition
* `i++` → move to next value

---

## 🧠 **How Loop Executes**

```text
Start → Check Condition → Run Code → Increment → Repeat
```

When condition becomes false → loop stops.

---

## 🔁 **Calling Functions Inside a Loop**

Calling a function inside a loop is **normal and common**.

Example:

```js
function greet() {
  console.log("Hello");
}

for (let i = 0; i < 3; i++) {
  greet();
}
```

Output:

```text
Hello
Hello
Hello
```

> Loops + functions = powerful combination.

---

## 📦 **Arrays and Loops**

Arrays store **multiple values**.
Loops help us **process each value one by one**.

Example:

```js
const numbers = [1, 2, 3, 4, 5];
```

Using loop:

```js
for (let i = 0; i < numbers.length; i++) {
  console.log(numbers[i]);
}
```

---

## 🔢 **Example: Print All Even Numbers in an Array**

```js
const arr = [1, 2, 3, 4, 5, 6, 7, 8];

for (let i = 0; i < arr.length; i++) {
  if (arr[i] % 2 === 0) {
    console.log(arr[i]);
  }
}
```

Explanation:

* Loop goes through each element
* `if` checks even condition
* Only even numbers are printed

---

## 🧠 **Key Takeaways**

* Loops automate repetition
* `for` loop has 3 parts
* Loops work very well with arrays
* Functions can be called inside loops
* Conditions control loop behavior

---

## ✍️ **Practice Tasks (Must Do)**

* ✅ Print numbers from 1 to 10 using a loop
* ✅ Print all elements of an array
* ✅ Print only even numbers from an array
* 🔁 Try changing loop conditions and observe output

Practice here:
👉 [https://namastedev.com/playground](https://namastedev.com/playground)

---

✨ **Loops save time.
Arrays store data.
Together, they solve real problems.** 🚀
