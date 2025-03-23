# Day 1: Introduction to CSS

Welcome to **Day 1** of your CSS learning journey! Today, we will cover the fundamentals of CSS, including its syntax, types, and selectors in a structured manner.

---
## **1. What is CSS?**
CSS (**Cascading Style Sheets**) is a stylesheet language used to control the presentation and layout of HTML documents. It allows developers to style web pages efficiently and make them visually appealing.

### **1.1 Why Use CSS?**
- 🎨 **Enhances Design**: Adds colors, fonts, spacing, and animations.
- 🏗 **Separates Structure & Style**: Keeps HTML clean and focused on content.
- 📱 **Enables Responsive Design**: Adapts layouts for different devices.
- ⚡ **Improves Performance**: Reduces code duplication and enhances maintainability.
- 🔄 **Reusable Styles**: One CSS file can be applied to multiple HTML pages.

---
## **2. CSS Syntax & Structure**
A CSS rule consists of **a selector** and **a declaration block**.

```css
selector {
  property: value;
  property: value;
}
```

### **Example:**
```css
h1 {
  color: blue;
  font-size: 24px;
}
```
📌 Here:
- `h1` → **Selector** (targets `<h1>` elements)
- `color: blue;` → **Declaration** (sets text color to blue)
- `font-size: 24px;` → **Declaration** (sets font size to 24 pixels)

---
## **3. Types of CSS**
There are **three** main ways to apply CSS to a webpage:

### **3.1 Inline CSS (Least Recommended)**
CSS applied directly inside an HTML tag using the `style` attribute.
```html
<p style="color: red; font-size: 20px;">This is inline CSS.</p>
```
✅ Quick for small changes but **not reusable**.

### **3.2 Internal CSS**
CSS written inside the `<style>` tag in an HTML document.
```html
<style>
  p {
    color: green;
    font-size: 18px;
  }
</style>
```
✅ Useful for styling single-page projects.

### **3.3 External CSS (Best Practice)**
CSS stored in a separate `.css` file and linked to HTML.
```html
<link rel="stylesheet" href="styles.css">
```
✅ **Highly recommended** for maintainability and scalability.

---
## **4. CSS Selectors (Targeting Elements)**
CSS selectors define which elements the styles apply to.

### **4.1 Universal Selector (`*`)**
Targets **all** elements on a webpage.
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

### **4.2 Element Selector**
Styles a specific HTML element type.
```css
h1 {
  color: blue;
}
```

### **4.3 Class Selector (`.`)**
Used to style multiple elements with the same class name.
```css
.text-large {
  font-size: 24px;
  font-weight: bold;
}
```
Usage in HTML:
```html
<p class="text-large">This is large text.</p>
```

### **4.4 ID Selector (`#`)**
Used for a **unique** element (each ID must be unique per page).
```css
#main-title {
  color: red;
  text-align: center;
}
```
Usage in HTML:
```html
<h1 id="main-title">Main Title</h1>
```

### **4.5 Grouping Selector**
Applies the same styles to multiple elements at once.
```css
h1, p, button {
  font-family: Arial, sans-serif;
}
```

### **4.6 Descendant Selector**
Styles an element **inside** another element.
```css
div p {
  color: gray;
}
```
📌 Styles `<p>` inside `<div>`, but not `<p>` outside `<div>`.

### **4.7 Child Selector (`>`)**
Targets **direct** child elements.
```css
div > p {
  font-weight: bold;
}
```

---
## **5. Key Takeaways**
✅ CSS controls the **visual presentation** of web pages.
✅ CSS rules follow a `selector { property: value; }` structure.
✅ **Three types of CSS**: Inline, Internal, and External (**External is best**).
✅ CSS **selectors** help target specific elements for styling.
✅ **Prefer class selectors (`.`) over ID selectors (`#`)** for flexibility.


