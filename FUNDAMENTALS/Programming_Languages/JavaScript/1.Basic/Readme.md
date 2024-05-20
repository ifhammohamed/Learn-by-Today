## 1. Variables

Variables are used to store data values. In JavaScript, we can declare variables using `var`, `let`, and `const` keywords.

### Declaration

```javascript
let age = 23;
console.log("🚀 ~ age:", age);

let year = 2024;
console.log("🚀 ~ year:", year);

age = 30;
console.log("🚀 ~ age:", age);

const points = 100;
console.log("🚀 ~ points:", points);

// points = 50; // Error
// console.log("🚀 ~ points    :", points);
// Uncaught TypeError: Assignment to constant variable.

var score = 75;
console.log("🚀 ~ score:", score);

score = 45;
console.log("🚀 ~ score:", score);
// Older way of declaring variables

// let score = 100; // Error
// console.log("🚀 ~ score:", score);
// Uncaught SyntaxError: Identifier 'score' has already been declared (at index.js:22:5)
```

The changes made in this involve adding code snippets that demonstrate the declaration of variables using let, const, and var in JavaScript. It showcases how to assign values, reassign them, and the behavior of constants in JavaScript.

---
