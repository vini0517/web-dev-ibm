# Module 2 Summary: HTML – The Language of the Web

## 🎯 Learning Objectives
- Describe key developments in the history of HTML
- Identify the structure of HTML documents
- Explain the presentation function of HTML

---

## 📜 History of HTML

### ➤ GML (Generalized Markup Language)
- Developed by IBM in the 1960s.
- Used schema to describe document structure (e.g., `:h1.`).
- No closing tags; tags used colons and periods.

### ➤ SGML (Standardized Generalized Markup Language)
- Developed by Charles Goldfarb.
- Introduced angle brackets (`< >`) and nested tags.
- More permissive than HTML.

### ➤ HTML (HyperText Markup Language)
- Created by Tim Berners-Lee in 1989.
- Based on SGML, used for presenting web content in browsers.
- Introduced closing tags and hyperlinking.

---

## 🧱 HTML Document Structure

### Structure of an HTML Document:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Title of the document</title>
  </head>
  <body>
    <!-- Main content here -->
  </body>
</html>
```

### Key Components:
- `<html>`: Root tag for the document.
- `<head>`: Contains metadata, scripts, stylesheets.
- `<body>`: Contains visible content (text, images, etc).

### Schema:
- Describes structure and rules for valid HTML.
- Ensures well-formed documents.

---

## 🔖 HTML Tag Structure

### Elements:
- Tags are enclosed in `< >`, usually paired (`<tag></tag>`).
- Example: `<strong>Important</strong>`

### Attributes:
- Add extra information to elements.
- Format: `name="value"`

#### Common Attribute Types:
- **Style**: CSS inline styles (e.g., `style="color:red;"`)
- **Resource**: Link resources (e.g., `href`, `src`)
- **Events**: JavaScript triggers (e.g., `onclick`)
- **Metadata**: Info about elements (e.g., `type="button"`)

---

## 🎨 Presentation & Formatting in HTML

### HTML is a Declarative Language
- Describes **what** to present, not **how** to do it.
- Example:
  ```html
  <i>Italic text</i>
  ```

### HTML Parsers:
- Software that interprets HTML tags and renders content in browsers.

### Tags for Presentation:
- `<i>` and `<b>`: Italic and bold.
- `<em>` and `<strong>`: Preferred for semantic and accessible emphasis.

---

## 🔄 HTML Evolution

- Modern HTML (esp. HTML5) blends structure, data, and interactivity.
- Greater browser compatibility and accessibility.
- Semantic elements like `<em>` and `<strong>` enhance user experience.

---

## 🧠 Review Flashcards

| Question | Answer |
|---------|--------|
| What term refers to how browsers format and create interactions? | Presentation |
| What language describes formatting but not processing? | Declarative |
| What is a software that examines HTML text and separates elements? | Parser |
