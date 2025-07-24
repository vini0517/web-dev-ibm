# Module 5 Summary: Function of JavaScript – Interaction

## 📜 What is a Scripting Language?

- A **scripting language** automates tasks and adds interactivity to web pages.
- **Compared to compiled languages**:
  - **Scripting languages**: Interpreted line-by-line at runtime (e.g., JavaScript).
  - **Compiled languages**: Translated to machine code before execution (e.g., C++).
- **Pros**:
  - Easy to edit and deploy.
  - Human-readable.
- **Cons**:
  - Slower execution than compiled languages.

## 🕹️ What Does JavaScript Do?

- Adds **interactivity** to websites (buttons, forms, drag-and-drop, etc.).
- Can:
  - Detect and respond to **events** (e.g., `onclick`, `onchange`).
  - Show messages (e.g., `alert("Hi there!")`).
  - Manipulate HTML and CSS dynamically.

### Example Code Snippet

```html
<button onclick="sayHello()">Click</button>

<script>
function sayHello() {
  alert("Hi there!");
}
</script>
```

## 🕰️ History of JavaScript

- **Created by** Brendan Eich at **Netscape** in 1995.
- Originally intended for dynamic HTML pages.
- Standardized as **ECMAScript** by **ECMA International**.
- Frequently updated with **backward compatibility**.
- **Not related to Java** — name similarity is marketing-driven.
- **TypeScript**: A superset of JavaScript developed by Microsoft, compiles to JavaScript.

## 🔁 JavaScript + HTML + CSS

JavaScript interacts closely with HTML and CSS:

### JavaScript & HTML
- Can **create, modify, or remove HTML elements** dynamically.
- Uses selectors like `document.querySelector()` to access elements.

### JavaScript & CSS
- Can change styles dynamically:
  ```js
  document.querySelector("#box").style.backgroundColor = "blue";
  ```

### Example: Validating a Form
```html
<input id="firstName" />
<button onclick="checkForm()">Submit</button>

<script>
function checkForm() {
  let name = document.querySelector('#firstName').value;
  if (name === "") {
    alert("First name is required.");
  }
}
</script>
```

## ✅ Matching Capabilities

| Task | Technology |
|------|------------|
| Set page structure, add image, hyperlink | HTML |
| Set text color, background, layout | CSS |
| Respond to click, drag, form submit | JavaScript |

## 📊 Popularity

- JavaScript is the **most-used programming language** (Stack Overflow 2022).
- Powers modern web applications with dynamic behavior and real-time interaction.
