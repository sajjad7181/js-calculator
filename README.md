# Simple JavaScript Calculator

This is a basic calculator built using **HTML**, **JavaScript**, and **Bootstrap 4**.  
It allows users to perform simple arithmetic operations: **add, subtract, multiply, divide**.

---

## 🧠 Key Learning Points

- DOM manipulation with `getElementById`
- Event handling using `onclick`
- Handling `NaN` and `division by zero`
- Bootstrap for quick UI styling
- Using `parseFloat()` to convert input strings to numbers

---

## 💡 JS Tip: Division by Zero

In JavaScript:

```js
"2" / "0"  // returns Infinity
```

Why?
Because inputs from <input type="number"> come in as strings by default,
and "0" !== 0 is true.

So this condition fails:
```js
if (num2 !== 0) // true, because "0" !== 0
```

To fix this, always convert values to numbers using parseFloat() or Number():
```js
let num2 = parseFloat(document.getElementById("num2").value);
```
