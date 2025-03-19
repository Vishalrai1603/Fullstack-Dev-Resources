# Day 4: Links & Images in HTML

## 1. Hyperlinks (Links)
### Basic Link:
```html
<a href="https://www.example.com">Visit Example</a>
```
- The `<a>` tag defines a hyperlink.
- The `href` attribute specifies the destination URL.

### Open Link in a New Tab:
```html
<a href="https://www.example.com" target="_blank">Open in New Tab</a>
```
- `target="_blank"` makes the link open in a new tab.

### Internal Links (Same Page):
```html
<a href="#section2">Jump to Section 2</a>
<h2 id="section2">Section 2</h2>
```
- `id` is used to create a bookmark within the same page.

### Email & Phone Links:
```html
<a href="mailto:someone@example.com">Send Email</a>
<a href="tel:+123456789">Call Us</a>
```
- `mailto:` opens an email client.
- `tel:` allows calling directly on supported devices.

---

## 2. Adding Images
### Basic Image:
```html
<img src="image.jpg" alt="Description of Image">
```
- `src`: Specifies the image location.
- `alt`: Provides alternative text for accessibility.

### Adjusting Image Size:
```html
<img src="image.jpg" width="300" height="200">
```
- You can set width and height directly.

### Responsive Image:
```html
<img src="image.jpg" style="max-width:100%; height:auto;">
```
- Ensures the image scales correctly on different screens.

### Image as a Link:
```html
<a href="https://www.example.com">
    <img src="button.jpg" alt="Click Here">
</a>
```
- Clicking the image will navigate to the specified link.
---
---

## **Practice Task:**
1. Create a webpage with 3 links:
   - An external website link.
   - A link that opens in a new tab.
   - A link that jumps to a section in the same page.
2. Add two images:
   - One with fixed dimensions.
   - One that is responsive.
3. Create an image that acts as a hyperlink.
4. Implement a practical HTML page using all these concepts.