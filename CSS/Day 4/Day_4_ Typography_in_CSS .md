# Day 4: Typography in CSS (Fonts, Text Styling, Line Height, Letter Spacing)

Welcome to **Day 4** of your CSS journey! Today, we will explore **Typography in CSS**, which plays a vital role in designing beautiful and readable web pages.

Typography includes:
- Choosing the right **fonts**
- Applying different **text styles**
- Adjusting **line height** for readability
- Managing **letter spacing** and **word spacing**

Let's dive into each of these aspects in detail. 🚀

---

## **1. Fonts in CSS**
Fonts define how text appears on a webpage. In CSS, you can specify fonts using the `font-family` property.

### **1.1 Font Family**
The `font-family` property allows you to specify different fonts for an element. It is a good practice to use **fallback fonts** in case the preferred font is unavailable.

```css
p {
    font-family: Arial, Helvetica, sans-serif;
}
```
- **Arial** is the primary font.
- **Helvetica** is the fallback if Arial is not available.
- **sans-serif** ensures a generic font is used if both are unavailable.

### **1.2 Web Safe Fonts**
Web safe fonts are fonts that are commonly available on most operating systems:
- `Arial, Helvetica, sans-serif`
- `Times New Roman, Times, serif`
- `Courier New, Courier, monospace`
- `Georgia, serif`
- `Verdana, sans-serif`

### **1.3 Custom Fonts (Google Fonts)**
To use a custom font from **Google Fonts**, import it in your CSS:

```css
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

body {
    font-family: 'Roboto', sans-serif;
}
```
This loads the **Roboto** font from Google Fonts and applies it to the entire webpage.

---

## **2. Text Styling in CSS**

### **2.1 Font Size**
The `font-size` property controls the size of the text. You can use different units:
```css
h1 {
    font-size: 36px; /* Pixels */
}
p {
    font-size: 1.2em; /* Relative to parent element */
}
```
- **px** (Pixels): Fixed size.
- **em**: Relative to the parent element.
- **rem**: Relative to the root (`html`) element.

### **2.2 Font Weight**
The `font-weight` property defines how bold or light a font appears.
```css
h1 {
    font-weight: bold;
}
p {
    font-weight: 300; /* Thin */
}
```
Common values:
- `normal`
- `bold`
- `lighter`
- `100 - 900` (Numerical values, where 400 is normal and 700 is bold)

### **2.3 Font Style**
The `font-style` property allows you to make text italic or oblique.
```css
p {
    font-style: italic;
}
```

### **2.4 Text Decoration**
Used to underline, overline, or strike through text.
```css
a {
    text-decoration: none; /* Removes underline from links */
}
```
- `underline`
- `overline`
- `line-through`
- `none`

### **2.5 Text Transformation**
Controls how text appears (uppercase, lowercase, capitalize).
```css
h1 {
    text-transform: uppercase;
}
```
- `uppercase` (ALL CAPS)
- `lowercase` (all small letters)
- `capitalize` (First Letter Capitalized)

---

## **3. Line Height & Letter Spacing**

### **3.1 Line Height (Spacing Between Lines)**
The `line-height` property improves readability by adjusting the space between lines.
```css
p {
    line-height: 1.5;
}
```
📌 **Best Practices:**
- `1.5` to `1.8` is considered a good line height for readability.

### **3.2 Letter Spacing & Word Spacing**
The `letter-spacing` property controls space between letters:
```css
h1 {
    letter-spacing: 2px;
}
```
The `word-spacing` property controls space between words:
```css
p {
    word-spacing: 5px;
}
```

---

## **4. Key Takeaways**
- Use `font-family` to choose fonts and add fallbacks.
- Adjust `font-size` and `font-weight` for emphasis.
- Use `line-height` and `letter-spacing` to improve readability.
- Apply `text-transform` to style text appearance.
- Use `@import` to add Google Fonts.

---

