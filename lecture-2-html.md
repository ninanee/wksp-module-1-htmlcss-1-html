# 1.1.2 - HTML or How To Make Lasagna*

---

_actually it's HyperText Markup Language_
<not a langudge, just a markup>
---

## Pop Quiz!

- What is HTML? content, markup, structure, what oy uhave to say
- What is CSS? style

---

## Pop Quiz!

- Which is more important?

<img src="./assets/batman_thinking.jpg" />

---

## Anatomy of an HTML element

<img src="./assets/html_element.png" />

---

## Anatomy of an HTML element

<img src="./assets/html_element_2.png" />

---

## Basic HTML Template

```HTML
<!DOCTYPE html>
<html>

    <head>
        <title>A Basic HTML Template</title>
    </head>
    <body>
        <!-- all content here -->
    </body>

</html>
```
only whars is a the "body" element will shoe on screen 

[More about the doctype.](https://www.w3schools.com/tags/tag_doctype.asp)

---

## Choosing the RIGHT tag for the job

Tags should be chosen based on the semantic value of the content
the content determins the tag

---

## Choosing the RIGHT tag for the job

Tags should NEVER be chosen based on presentation, or look

---

This means that these tags are essentially off-limits

`<big>`, `<small>`, `<i>`, `<b>`, `<br />`, `&nbsp;`, `<hr />`

They have no semantic value. but they pretend to.

---

Anytime you catch yourself thinking...

"I should use x because I need it to look like ..."

✋

---

### Semantic HTML = Google

1. It pleases Google.
    - Easier for its algorithm to crawl and index site
    - Meaning a better ranking in search results
    - Less of a need to "game" the Google algorithm

---

### Semantic HTML = Accessibility
goog HTML makes it easier for screenreaders to interpert the content and make it accesible.
<img src="./assets/accessibility_stats.png" />

---

### Semantic HTML = Accessibility

- [22% of Canadians over the age of 15% live with _at least_ one disability (6.2 million)](https://siteimprove.com/en-ca/blog/a-complete-overview-of-canada-s-accessibility-laws/).

---

### Semantic HTML = Accessibility

- [The Accessible Canada Act (Bill C-81)](https://www.parl.ca/DocumentViewer/en/42-1/bill/C-81/first-reading)

---

### Semantic HTML = Accessibility

- On June 21, 2019, The Accessible Canada Act became law after receiving Royal Assent.

---

### Semantic HTML = Accessibility

- Fines of up to $250,000. 😬

---

🙏 Always write good HTML. 🙏

---

## Common HTML Tags (4.01+)

- Block-level elements - each block in "under" the previous. a new line
    - `<h1>` -(there should be only one h1 on a page), `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`, `<p>`
    - `<ul>`, `<ol>`, `<li>`, `<blockquote>` - , `<table>` - kinda like spreadsheet,
    - `<form>` - filling a form
    - `<div>` - no semantic value, we use it a a box of contant for styling.
- Inline elements - won't move the contant to a new line
    - `<img>`, `<a>` - link, `<span>` - mini `<div>` for in line values, `<button>`
    - `<input>`, `<label>`, `<select>`, `<textarea>`
    - `<abbr>` - abbreviation, when hovering it will show ontop

[Source](https://www.w3resource.com/html/HTML-block-level-and-inline-elements.php)

---

## HTML 5 Semantic Tags

- `<header>`, `<footer>`, `<nav>`- navigation bar, `<section>`, `<main>` - the box of the sections and articles, `<aside>`
- `<figure>` - for example if the image in a chart r a gif, `<figcaption>`, `<summary>`
- `<time>`, 

---

## HTML 5 Semantic Tags

<img src="./assets/html5.png" />

---