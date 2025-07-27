## 🎨 Module 4: Coding with Style – Using CSS

### 📘 Introduction

In this module, you'll explore **Cascading Style Sheets (CSS)**—the language used to style web pages. You'll learn how CSS works with HTML, different ways to apply styles, and the structure of styles using selectors and declaration blocks.

---

### 🎯 Learning Objectives

By the end of this module, you will be able to:

* ✅ Define CSS and its purpose
* ✅ Explain how styles cascade (inheritance vs. override)
* ✅ Differentiate internal vs. external stylesheets
* ✅ Describe how to use ID, class, and element selectors
* ✅ Apply CSS to HTML elements using different methods

---

### 💡 What Is CSS?

CSS (Cascading Style Sheets) is used to define how HTML elements **look and feel**.

It controls:

* 🎨 Colors
* 🖋️ Fonts
* 📐 Layouts
* 🧩 Spacing and more

There are two ways to apply styles:

* **Inline styles** — using the `style` attribute inside an HTML tag
* **Stylesheets** — collections of styles (internal or external)

> CSS separates content (HTML) from presentation, making web documents easier to manage.

---

### 🔄 How Do Styles Cascade?

Styles can be **inherited** or **overridden** through parent-child relationships in HTML.

#### 🧬 Inherited Style

A child element inherits the style from its parent **if it doesn’t define its own**.

Example:

```html
<div style="margin-left:10px;">
  <p>This paragraph inherits the 10px margin.</p>
</div>
```

#### 🧧 Overridden Style

A child can override a parent’s style by declaring the same property with a new value.

Example:

```html
<div style="color:red;">
  <p style="color:blue;">This text will be blue.</p>
</div>
```

#### 🔁 Real-World Examples

**Inheritance:**

```html
<section style="margin-top: 20px;">
  <div style="margin-top: 10px;"></div>
</section>
```

**Override:**

```html
<span style="color:green;">
  <span style="color:black;">Hello there</span>
</span>
```

---

### ✍️ How Do Inline Styles Work?

Apply a style directly to an HTML element using the `style` attribute.

Example:

```html
<p style="text-decoration:underline;">Underline me</p>
```

⚠️ **Drawback**: Hard to maintain at scale. Repeating styles manually is inefficient.

---

### 📁 How Do Stylesheets Work?

CSS styles can be grouped into stylesheets:

#### 🔹 External Stylesheet

Defined in a `.css` file and linked via the `<link>` tag in `<head>`:

```html
<link href="pagestyle.css" rel="stylesheet">
```

In `pagestyle.css`:

```css
p {
  margin-left: 20px;
}
```

#### 🔸 Internal Stylesheet

Defined inside a `<style>` block within the `<head>`:

```html
<style>
  p {
    margin-left: 20px;
  }
</style>
```

✅ **Best Practice**: Use external stylesheets for maintainability.

---

### 🧬 Anatomy of a Style Rule

A CSS rule includes:

| Part                  | Description                                       |
| --------------------- | ------------------------------------------------- |
| **Selector**          | Targets HTML elements                             |
| **Node Name**         | The name of the element, class, or ID             |
| **Declaration Block** | Contains one or more declarations (style rules)   |
| **Declaration**       | A pair of property and value                      |
| **Property**          | What you want to change (e.g., `color`, `margin`) |
| **Value**             | The new value to assign (e.g., `red`, `10px`)     |

Example:

```css
.class-name {
  color: red;
  font-weight: bold;
}
```

---

### 🏷️ Types of CSS Selectors

| Selector    | Symbol   | Purpose                           |
| ----------- | -------- | --------------------------------- |
| **ID**      | `#`      | Unique to one element             |
| **Class**   | `.`      | Can apply to many elements        |
| **Element** | tag name | Targets all elements of that type |

#### 📌 ID Selector

```css
#font-style-bold {
  font-weight: bold;
}
```

Applied in HTML:

```html
<p id="font-style-bold">Bold text</p>
```

#### 📌 Class Selector

```css
.background-style-red {
  background-color: red;
}
```

Applied in HTML:

```html
<img class="background-style-red" src="/images/img1.jpg">
```

#### 📌 Element Selector

```css
div {
  margin-top: 20px;
  margin-right: 10px;
}
```

Applied automatically to all `<div>` elements.

---

### 📎 Combining Selectors

When duplicate selectors exist in a stylesheet, **styles are merged**:

```css
.style-alert-message {
  font-weight: bold;
}

.style-alert-message {
  font-style: italic;
}
```

➡️ Final style: text is **bold** and **italic**.

---

### ✅ Summary

* CSS defines the **visual style** of HTML elements.
* Styles can **inherit** or be **overridden** in parent-child structures.
* Use **inline styles** sparingly; prefer **stylesheets**.
* Understand the **anatomy** of a CSS rule: selector, property, value.
* Use **selectors** effectively: `id`, `class`, and `element`.

---
