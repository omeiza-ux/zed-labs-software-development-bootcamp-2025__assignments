# Inline and Block Elements in Frontend Development

In HTML and CSS, elements are divided into inline elements and block-level elements. This classification determines how elements are displayed on a webpage and how they interact with other elements. Understanding the difference is essential for proper frontend design, layout control, and styling.
## Block Elements
A block-level element always starts on a new line and takes up the full width available (by default). It creates a distinct block in the page layout.

### Examples
```html
<div>

<p>

<h1> to <h6>

<section>

<article>

<header> / <footer>

<ul>, <ol>, <li>
``` 
### Characteristics

- Always begins on a new line.

- Occupies the full width of the parent container (unless styled otherwise).

- Can contain other block elements and inline elements.
### Example
```html
<p>This is a paragraph. It is a block element.</p>
<div>This div also starts on a new line.</div>
```
## Inline Elements
An inline element does not start on a new line. It only takes up as much width as its content requires.

### Examples
```html
<span>

<a>

<strong>

<em>

<img>

<label>

<b>, <i>, <u>
```
### Characteristics

- Does not start on a new line.

- Takes up only the space needed by its content.

- Cannot contain block-level elements (only text or other inline elements).

### Example 
```html
<p>This is <span>an inline span</span> inside a block element.</p>
<a href="#">This is an inline link</a>
```