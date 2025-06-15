# Chapter 3 – Types, Values, and Variables

## 📌 Key Concepts & Notes

### 🔹 3.1 Overview and Definitions

- JavaScript values are divided into **primitive types** and **object types**.
- Primitive types: `number`, `string`, `boolean`, `null`, `undefined`, `symbol`, and `bigint`.
- Objects are mutable, while primitives are immutable.

### 🔹 3.2 Numbers

- JavaScript has a single number type (IEEE 754 double-precision floating point).
- Special numeric values include: `NaN`, `Infinity`, `-Infinity`.
- `parseInt()`, `parseFloat()` convert strings to numbers.
- Use `Number()`, `isNaN()`, and `isFinite()` for safer conversions and checks.

### 🔹 3.3 Text (Strings)

- Strings are immutable sequences of Unicode characters.
- Template literals (` ` ` `) allow for interpolation and multiline strings.
- Useful methods: `.length`, `.slice()`, `.toUpperCase()`, `.includes()`, etc.

### 🔹 3.4 Boolean Values

- Two possible values: `true` and `false`.
- Used in conditional logic, comparisons, and type coercion.

### 🔹 3.5 null and undefined

- `null`: explicit absence of a value.
- `undefined`: uninitialized variable or missing property.
- Commonly confused, but semantically different.

### 🔹 3.6 Symbols

- A special and unique primitive type introduced in ES6.
- Often used as object keys to avoid naming collisions.

### 🔹 3.7 The Global Object

- Each JS environment (browser, Node.js) provides a global object (`window`, `globalThis`, etc.).
- Global variables become properties of this object.

### 🔹 3.8 Immutable Primitive Values and Mutable Object References

- Primitives are copied by value.
- Objects are copied by reference.
- Changing an object through one variable affects all references to it.

### 🔹 3.9 Type Conversions

- **Implicit (coercion)** and **explicit (manual)** conversions exist.
- Use `String()`, `Number()`, and `Boolean()` for explicit conversion.
- Avoid relying too much on implicit coercion, especially with `==`.

### 🔹 3.10 Variable Declaration and Assignment

- Use `let` and `const` (block-scoped); avoid `var` (function-scoped).
- **Destructuring** lets you unpack values from arrays or objects into variables:
  ```js
  let [{ x: x1, y: y1 }, { x: x2, y: y2 }] = points;
  ```

### 🔹 3.11 Summary

- Learned how to work with JS primitive types and type conversions.
- Understood the difference between mutable and immutable values.
- Learned about scope, variable declarations, and destructuring.

### 🧠 New & Important Takeaways

- Destructuring syntax becomes clearer when you treat the LHS as a literal and flip the assignment.
- Symbols are useful for creating truly unique property keys.
- The global object can unintentionally be polluted by undeclared variables.
