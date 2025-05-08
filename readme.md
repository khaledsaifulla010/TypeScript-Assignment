# 🎯 TypeScript Interview Questions - Blog Task

## 1️⃣ What is type inference in TypeScript? Why is it helpful?

### Answer:

**Type inference** means TypeScript automatically guesses the type of a variable based on its value. You don’t always need to tell it the type manually.

### 🔍 Example:

```ts
let name = "Alice"; // TypeScript knows this is a string
let age = 25; // TypeScript knows this is a number
```

**Why is it helpful?**

1. Less code – You write fewer type annotations
2. Fewer errors – TypeScript catches type-related bugs early
3. Better readability – The code is cleaner and easier to read

## 2️⃣ How does TypeScript help in improving code quality and project maintainability?

### Answer:

**TypeScript** improves both code quality and project maintainability by adding type safety and helpful features on top of JavaScript. It helps catch errors early and makes code easier to manage, especially in large projects. <br>

**🛠 How it improves code quality:**

1.  Type checking – Warns you if you use the wrong data types
2.  Autocomplete – Your editor suggests correct code and functions
3.  Early error detection – Catches mistakes before the app runs
4.  Clear code contracts – You know exactly what data is expected

**🧩 How it helps maintainability:**

1. Easier refactoring – You can change parts of your code with confidence
2. Better team collaboration – Everyone understands the data structure
3. Scales well – Helpful in large codebases
4. Built-in documentation – Types explain how things work
