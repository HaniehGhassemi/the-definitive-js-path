# 🧪 Interpreted Language

JavaScript is an **interpreted** language, which means:

- It **executes code line by line**, at runtime.
- There's **no compilation step** ahead of time.
- The engine reads and runs statements one after another.

## 🎯 Goal of This Exercise

To **visualize how JavaScript runs code step by step**, we'll use an amazing tool called **Loupe**.

🔗 [Click here to open the example in Loupe](https://latentflip.com/loupe)

## 👀 What to Observe

Paste or run the following code in example.js

And watch for:

- How the JavaScript engine **executes one line at a time**.
- How the function `greet` is declared but **not executed until called**.
- When `greet("Hanieh")` runs, the argument `"Hanieh"` is passed and `"Hello Hanieh"` is logged.
- The order of output lines in the console:

  1. `"Start"`
  2. `"Hello Hanieh"`
  3. `"End"`

This demonstrates how JavaScript interprets code sequentially, but also how **function declarations are hoisted**, meaning the function can be called before or after its definition without error.

## ✅ Why This Matters

This example clearly demonstrates how JavaScript behaves as an **interpreted language** — executing each line sequentially as it reads it, without pre-compilation.

Use tools like **Loupe** to build a mental model of how JavaScript code flows during execution.
