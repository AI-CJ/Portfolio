# FreeCodeCamp Responsive Web Design Course Notes 

---

## **1. Introduction to Basic HTML and HTML5**
### **What is HTML?**
- HTML stands for **HyperText Markup Language** and is the backbone of any webpage.
- It describes the **structure** of a webpage using **elements** (building blocks of HTML).
- HTML is not a programming language; it is a **markup language**.

### **HTML Elements**
- An HTML element consists of:
  - **Opening tag:** `<tag>`
  - **Content:** Text or other elements nested inside.
  - **Closing tag:** `</tag>` (Not all tags have closing tags, e.g., `<img>`, `<br>`)
- Elements can also have **attributes**, which provide additional information about the element.
  - Example: `<a href="https://freecodecamp.org" target="_blank">FreeCodeCamp</a>`  
    - `href`: Specifies the link’s URL.
    - `target="_blank"`: Opens the link in a new tab.

### **Semantic HTML**
- Semantic elements clearly describe their purpose and make a website more accessible. Examples:
  - `<header>`: Contains introductory content, such as navigation links.
  - `<main>`: Represents the main content of the page.
  - `<footer>`: Contains footer information, such as contact details or copyright.

### **Key HTML Tags**
#### **Headings**
- `<h1>` to `<h6>` are used to define headings, with `<h1>` being the most important.
  - Example:
    ```html
    <h1>Main Heading</h1>
    <h2>Subheading</h2>
    ```

#### **Paragraphs**
- `<p>` defines paragraphs of text.
  - Example:
    ```html
    <p>This is a paragraph of text.</p>
    ```

#### **Links**
- `<a>` creates hyperlinks. 
  - Example:
    ```html
    <a href="https://example.com">Visit Example</a>
    ```

#### **Images**
- `<img>` embeds images. Always include the `alt` attribute for accessibility.
  - Example:
    ```html
    <img src="image.jpg" alt="Description of the image">
    ```

#### **Lists**
- **Ordered List (`<ol>`):** Displays items with numbers.
- **Unordered List (`<ul>`):** Displays items with bullet points.
  - Example:
    ```html
    <ul>
      <li>Item 1</li>
      <li>Item 2</li>
    </ul>
    ```

#### **Forms**
- `<form>` is used to collect user input.
- Common form elements:
  - `<input>`: Collects data (supports types like `text`, `password`, `email`, etc.).
  - `<textarea>`: Multi-line text input.
  - `<button>`: Submits the form.
  - Example:
    ```html
    <form action="/submit" method="POST">
      <label for="name">Name:</label>
      <input id="name" type="text" name="name" required>
      <button type="submit">Submit</button>
    </form>
    ```

---

## **2. Introduction to Basic CSS**
### **What is CSS?**
- CSS (Cascading Style Sheets) is used to control the **appearance** and **layout** of HTML.
- CSS separates **structure (HTML)** from **design (CSS)**.

### **How CSS Works**
- CSS is applied using **selectors** to target specific HTML elements.
  - Example:
    ```css
    h1 {
      color: blue;
      font-size: 24px;
    }
    ```
- **Inline:** Applied directly to an element using the `style` attribute.
  - Example: `<h1 style="color: red;">Hello</h1>`
- **Internal:** Written inside `<style>` tags in the `<head>` of the document.
  - Example:
    ```html
    <style>
      h1 {
        color: red;
      }
    </style>
    ```
- **External:** Stored in a separate `.css` file and linked using:
  ```html
  <link rel="stylesheet" href="styles.css">
