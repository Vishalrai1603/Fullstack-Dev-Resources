# Day 2: Colors, Backgrounds, and Borders

Welcome to **Day 2** of your CSS journey! Today, we will explore how to use colors, set backgrounds, and add borders to elements in detail.

---
## **1. Understanding Colors in CSS**
Colors play a crucial role in web design, affecting readability, aesthetics, and user experience. CSS provides multiple ways to define colors.

### **1.1 Color Naming System**
CSS supports **140+ predefined color names** such as `red`, `blue`, `green`, `orange`, etc.
```css
h1 {
  color: blue;
}
```
🔹 Simple and easy to remember but limited in customization.

### **1.2 Hexadecimal Color Codes**
A hex color is a six-digit combination of red, green, and blue values, prefixed with `#`.
```css
p {
  color: #ff5733; /* Orange-red */
}
```
🛠 **Hex Shortcut:** If all pairs are the same, they can be shortened. Example: `#ff5733` → `#f53`.

### **1.3 RGB (Red, Green, Blue) Colors**
Uses numeric values from `0` to `255` for red, green, and blue.
```css
div {
  color: rgb(255, 0, 0); /* Pure red */
}
```
🎯 Good for dynamically changing colors with JavaScript.

### **1.4 RGBA (Adding Transparency)**
RGBA adds an **alpha** channel (transparency) ranging from `0` (fully transparent) to `1` (fully opaque).
```css
h2 {
  color: rgba(0, 128, 0, 0.5); /* Semi-transparent green */
}
```

### **1.5 HSL (Hue, Saturation, Lightness) Colors**
- **Hue (0-360 degrees):** Defines color type (0=Red, 120=Green, 240=Blue)
- **Saturation (0-100%):** Intensity of the color
- **Lightness (0-100%):** Brightness level
```css
span {
  color: hsl(200, 100%, 50%); /* Bright blue */
}
```
🎨 **HSLA** adds an alpha transparency like RGBA.

---
## **2. Backgrounds in CSS**
Background properties help define the visual appearance of an element.

### **2.1 Background Color**
Sets a solid background color.
```css
body {
  background-color: lightgray;
}
```

### **2.2 Background Image**
Sets an image as the background.
```css
div {
  background-image: url('background.jpg');
}
```

### **2.3 Background Repeat**
Controls repetition of the background image.
```css
div {
  background-repeat: no-repeat; /* No repeating */
}
```
🔹 Options: `repeat`, `repeat-x`, `repeat-y`, `no-repeat`.

### **2.4 Background Position**
Defines where the background image starts.
```css
div {
  background-position: center top;
}
```
🔹 Keywords: `left`, `right`, `top`, `bottom`, `center`, or pixel values.

### **2.5 Background Size**
Defines how the background image is sized.
```css
div {
  background-size: cover; /* Covers the entire element */
}
```
🔹 Values: `auto`, `contain`, `cover`, or pixel values.

### **2.6 Background Attachment**
Determines if the background moves with the page.
```css
body {
  background-attachment: fixed;
}
```
🔹 Values: `scroll`, `fixed`, `local`.

---
## **3. Borders in CSS**
Borders help define the boundary of an element and enhance visual design.

### **3.1 Border Style**
Defines the type of border.
```css
div {
  border-style: solid;
}
```
🔹 Options: `solid`, `dashed`, `dotted`, `double`, `groove`, `ridge`, `inset`, `outset`, `none`.

### **3.2 Border Width**
Controls the thickness of the border.
```css
p {
  border-width: 3px;
}
```

### **3.3 Border Color**
Changes the color of the border.
```css
h1 {
  border-color: red;
}
```

### **3.4 Border Shorthand Property**
You can combine all border properties.
```css
div {
  border: 2px solid black;
}
```

### **3.5 Border Radius (Rounded Corners)**
Creates rounded corners for elements.
```css
button {
  border-radius: 10px;
}
```
🔹 `50%` makes a circular shape.

---

---
## **4. Key Takeaways**
- ✅ Multiple color methods: `Hex`, `RGB`, `HSL`, and transparency variations.
- ✅ Background properties control colors, images, positioning, and behavior.
- ✅ Borders define element boundaries and can have different styles.
- ✅ Border-radius creates rounded corners for softer design.

---
