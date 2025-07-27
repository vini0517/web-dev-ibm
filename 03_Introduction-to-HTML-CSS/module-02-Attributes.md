## 🧩 Module 2: Controlling Elements with Attributes

### 📘 Overview

This module teaches how HTML **attributes** are used to control and enhance elements on a web page. You’ll learn how to style, link, interact, and provide additional information to elements using attributes.

---

### 🎯 Learning Objectives

After completing this module, you’ll be able to:

* Define HTML attributes.
* Use attributes to style and control elements.
* Identify common attributes and their functions.

---

### 🔖 What Are Attributes?

Attributes add **extra information** to HTML elements and modify how they appear or behave.
They are written inside the **opening tag** of an element.

```html
<p style="color:green;">This text is green</p>
```

---

### 💡 What Can Attributes Do?

Attributes can be used to:

* 🎨 **Style elements** (e.g., `style`, `class`, `id`)
* 🌐 **Link content** (e.g., `href`, `src`)
* ⚙️ **Make elements interactive** (e.g., `onclick`, `onkeypress`)
* 🧠 **Provide metadata** (e.g., `aria-label`, `autofocus`)

---

### 🧬 Attributes of Attributes

Some attributes (like `style`) can have **properties**:

```html
<p style="color:green; font-weight:bold;">Bold green text</p>
```

Here:

* `style` is the attribute.
* `color` and `font-weight` are **properties** of the `style` attribute.

---

### ❓ Quick Tip

🟢 **Where do you place an attribute?**
✔️ Inside the **opening tag** of an element.

---

### 🔁 Common HTML Attributes

#### 🎨 Style and Layout Attributes

| Attribute    | Purpose                                            |
| ------------ | -------------------------------------------------- |
| `style`      | Applies inline CSS styles                          |
| `id`         | Unique identifier (used for styling or scripting)  |
| `class`      | Applies a shared style to multiple elements        |
| `display`    | Controls layout behavior (`inline`, `block`, etc.) |
| `aria-label` | Adds accessibility label for screen readers        |

#### ⚙️ Action Attributes

| Attribute   | Purpose                                                   |
| ----------- | --------------------------------------------------------- |
| `href`      | Specifies link destination (used in `<a>`)                |
| `src`       | Specifies media source (used in `<img>`, `<video>`, etc.) |
| `autofocus` | Automatically focuses element on page load                |
| `draggable` | Enables drag-and-drop behavior                            |

#### 🖱️ Event Attributes

| Attribute    | Trigger                              |
| ------------ | ------------------------------------ |
| `onclick`    | When the element is clicked          |
| `onerror`    | When an error occurs                 |
| `onkeypress` | When a key is pressed                |
| `onscroll`   | When the page or element is scrolled |

---

### ✅ Summary

* Attributes modify HTML elements and control behavior and appearance.
* They're written inside the opening tag.
* Common categories: **Style/Layout**, **Actions**, **Events**, and **Metadata**.
* Learning attribute syntax helps you create dynamic, accessible, and styled web pages.

---
