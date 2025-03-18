# Day 3: Text Formatting & Lists in HTML

## Text Formatting Tags:
HTML provides various text formatting tags to style text content.

```html
<p>This is <b>bold</b>, <i>italic</i>, and <u>underlined</u> text.</p>
<p><strong>Strong</strong> and <em>Emphasized</em> text.</p>
<p>This is <mark>highlighted</mark> text.</p>
<p>This is <small>small</small>.</p>
<p>This text is <del>deleted</del> and <ins>inserted</ins>.</p>
<p>This is <sub>subscript</sub> and <sup>superscript</sup> text.</p>
```
### Explanation:
- `<b>`: Makes text bold.
- `<i>`: Makes text italic.
- `<u>`: Underlines text.
- `<strong>`: Indicates strong importance (SEO-friendly).
- `<em>`: Emphasizes text.
- `<mark>`: Highlights text.
- `<small>`: Displays smaller text.
- `<del>`: Strikethrough (deleted text).
- `<ins>`: Underlined (inserted text).
- `<sub>`: Subscript text.
- `<sup>`: Superscript text.

---

## Lists in HTML:
### Ordered List (Numbered)
Ordered lists display items in sequential order.
```html
<ol>
    <li>Step 1</li>
    <li>Step 2</li>
    <li>Step 3</li>
</ol>
```

### Unordered List (Bulleted)
Unordered lists display items with bullets.
```html
<ul>
    <li>Item A</li>
    <li>Item B</li>
    <li>Item C</li>
</ul>
```

### Description List (Definition List)
Used to define terms with descriptions.
```html
<dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language</dd>
    <dt>CSS</dt>
    <dd>Cascading Style Sheets</dd>
</dl>
```

### Nested List
Lists can be nested inside each other.
```html
<ul>
    <li>Fruits
        <ul>
            <li>Apple</li>
            <li>Banana</li>
            <li>Orange</li>
        </ul>
    </li>
    <li>Vegetables
        <ul>
            <li>Carrot</li>
            <li>Broccoli</li>
        </ul>
    </li>
</ul>
```

---

## **Practice Task:**
1. Create an HTML file.
2. Add different types of text formatting tags.
3. Include an ordered list, unordered list, and a description list.
4. Try creating a nested list with at least 3 levels.
