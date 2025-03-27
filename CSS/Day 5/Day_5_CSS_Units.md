# Day 5: CSS Units (px, em, rem, %, vh, vw)

Welcome to **Day 5** of your CSS journey! Today, we will explore **CSS units**, which define measurements like font size, width, height, and spacing. Understanding CSS units is essential for creating responsive, scalable, and well-structured layouts.

---

## **1. Types of CSS Units**
CSS units can be categorized into two main types:

### **1.1 Absolute Units**
Absolute units are fixed in size and do not change based on screen size or parent elements.

| Unit | Description | Example |
|------|------------|---------|
| `px` | Pixels | `font-size: 16px;` |
| `pt` | Points (used in print) | `font-size: 12pt;` |
| `cm` | Centimeters | `width: 10cm;` |
| `mm` | Millimeters | `margin: 5mm;` |
| `in` | Inches | `width: 2in;` |

📌 **Most commonly used:** `px`

### **1.2 Relative Units**
Relative units scale dynamically based on viewport size, parent elements, or root elements.

| Unit | Relative To | Example |
|------|------------|---------|
| `em` | Parent element | `font-size: 1.5em;` |
| `rem` | Root `<html>` element | `font-size: 2rem;` |
| `%` | Parent container | `width: 50%;` |
| `vh` | Viewport height | `height: 50vh;` |
| `vw` | Viewport width | `width: 50vw;` |

📌 **Best for responsive design:** `em`, `rem`, `%`, `vh`, `vw`

---

## **2. Understanding Each Unit in Detail**

### **2.1 Pixels (`px`)**
- Fixed-size unit that does not change based on screen size or user settings.
- Example:
  ```css
  p {
      font-size: 16px; /* Always 16 pixels */
  }
  ```
📌 **Best for precise control but not recommended for fully responsive designs.**

### **2.2 EM (`em`) - Relative to Parent Element**
- `1em` = font size of the parent element.
- Useful for nested scaling, but can cause unintended scaling issues if overused.
- Example:
  ```css
  body {
      font-size: 16px;
  }
  p {
      font-size: 1.5em; /* 1.5 * 16px = 24px */
  }
  ```
📌 **Avoid deep nesting with `em` to prevent unintended scaling.**

### **2.3 REM (`rem`) - Relative to Root Element**
- `1rem` = font size of `<html>` (default is 16px).
- Ensures consistent scaling across the entire webpage.
- Example:
  ```css
  html {
      font-size: 16px;
  }
  p {
      font-size: 2rem; /* 2 * 16px = 32px */
  }
  ```
📌 **Best for consistency and accessibility.**

### **2.4 Percentage (`%`)**
- Used to define width, height, margins, padding, etc., relative to the parent element.
- Example:
  ```css
  div {
      width: 50%; /* Half of parent container */
  }
  ```
📌 **Useful for fluid layouts that adjust to screen size.**

### **2.5 Viewport Height & Width (`vh` & `vw`)**
- `1vh` = 1% of viewport height.
- `1vw` = 1% of viewport width.
- Example:
  ```css
  div {
      width: 50vw; /* 50% of the viewport width */
      height: 80vh; /* 80% of the viewport height */
  }
  ```
📌 **Great for full-page sections and dynamic resizing.**

---
---

## **3. Key Takeaways**
✅ Use `px` for fixed sizes.
✅ Use `em` for relative scaling to parent.
✅ Use `rem` for consistency and better accessibility.
✅ Use `%` for flexible layout sizing.
✅ Use `vh` & `vw` for viewport-based scaling.
✅ Combine different units for best results.

---

