# Day 6: HTML5 Semantic Elements

## Introduction

Semantic elements in HTML5 provide meaning to the structure of a webpage, making it more readable for both developers and search engines. Unlike generic `<div>` and `<span>` tags, semantic tags describe their purpose clearly, enhancing accessibility and SEO.

---

## Why Use Semantic Elements?

1. **Better Readability**: Developers can understand the structure at a glance.
2. **SEO Optimization**: Search engines prioritize semantic elements for indexing.
3. **Improved Accessibility**: Screen readers interpret content better.
4. **Easier Maintenance**: Organized code is easier to debug and scale.

---

## Semantic Tags and Their Usage

### 1. `<header>`

- Represents the introductory content of a webpage or a section.
- Often contains the website logo, heading, and navigation links.
- Can be used multiple times in a document (e.g., for sections and articles).

#### Example:

```html
<header>
    <h1>My Website</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>
```

---

### 2. `<nav>`

- Defines a section for navigation links.
- Typically contains links to different pages or sections within the same page.

#### Example:

```html
<nav>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>
```

---

### 3. `<section>`

- Represents a standalone section of a webpage.
- Often used to divide content into meaningful parts.
- Commonly used inside `<article>` elements to group content logically.

#### Example:

```html
<section>
    <h2>About Us</h2>
    <p>We are a tech company providing web solutions.</p>
</section>
```

---

### 4. `<article>`

- Represents independent, self-contained content like blog posts or news articles.
- Useful for syndication and sharing.
- Should be meaningful even when taken out of context.

#### Example:

```html
<article>
    <h2>Latest News</h2>
    <p>New HTML5 features are making web development easier!</p>
</article>
```

---

### 5. `<aside>`

- Represents content that is related but not the main focus, such as sidebars.
- Often used for advertisements, related links, or additional info.

#### Example:

```html
<aside>
    <h3>Related Articles</h3>
    <ul>
        <li><a href="#">HTML Basics</a></li>
        <li><a href="#">CSS Fundamentals</a></li>
    </ul>
</aside>
```

---

### 6. `<footer>`

- Defines the footer of a webpage or a section.
- Typically contains copyright information, links, or contact details.
- Can appear multiple times in a webpage.

#### Example:

```html
<footer>
    <p>&copy; 2025 My Website. All Rights Reserved.</p>
</footer>
```

---

## Multimedia in HTML5

HTML5 introduced `<audio>` and `<video>` elements for embedding multimedia without requiring third-party plugins.

### 1. Embedding Video

- The `<video>` tag is used to embed videos with support for multiple formats.
- The `controls` attribute adds play, pause, and volume options.
- Supports additional attributes like `autoplay`, `loop`, and `muted`.

#### Example:

```html
<video controls width="600">
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

---

### 2. Embedding Audio

- The `<audio>` tag allows embedding audio files like MP3 and OGG.
- The `controls` attribute provides playback controls.
- Additional attributes include `autoplay`, `loop`, and `muted`.

#### Example:

```html
<audio controls>
    <source src="audio.mp3" type="audio/mp3">
    Your browser does not support the audio element.
</audio>
```

---

## Additional Semantic Elements in HTML5

### 1. `<figure>` and `<figcaption>`

- Used to associate images with captions.

#### Example:

```html
<figure>
    <img src="image.jpg" alt="Description">
    <figcaption>Image description here</figcaption>
</figure>
```

### 2. `<main>`

- Represents the main content of a webpage, excluding repeated sections like headers and footers.

#### Example:

```html
<main>
    <h2>Welcome to My Website</h2>
    <p>This is the main content area.</p>
</main>
```

### 3. `<mark>`

- Highlights text to indicate relevance.

#### Example:

```html
<p>Learning <mark>HTML5</mark> is essential for web development.</p>
```

---



