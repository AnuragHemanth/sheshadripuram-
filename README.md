# sheshadripuram-
The notes for the students of sheshadripuram college BCA
# HTML Notes
## Full Stack Development - BCA

---

# What is HTML?

**HTML (HyperText Markup Language)** is the standard markup language used to create web pages.

HTML defines the structure of a webpage using **elements (tags)**.

Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Page</title>
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
```

---

# Basic Structure of HTML

```html
<!DOCTYPE html>
<html>

<head>
    <title>Page Title</title>
</head>

<body>

</body>

</html>
```

| Tag | Purpose |
|------|----------|
| `<!DOCTYPE html>` | Declares HTML5 document |
| `<html>` | Root element |
| `<head>` | Contains metadata |
| `<title>` | Browser tab title |
| `<body>` | Visible webpage content |

---

# Headings

```html
<h1>Main Heading</h1>
<h2>Heading</h2>
<h3>Heading</h3>
<h4>Heading</h4>
<h5>Heading</h5>
<h6>Heading</h6>
```

`<h1>` is the largest heading.

`<h6>` is the smallest.

---

# Paragraph

```html
<p>This is a paragraph.</p>
```

---

# Line Break

```html
<br>
```

Moves content to the next line.

---

# Horizontal Line

```html
<hr>
```

Creates a horizontal separator.

---

# Comments

```html
<!-- This is a comment -->
```

Comments are ignored by the browser.

---

# Text Formatting Tags

### Bold

```html
<b>Bold Text</b>
```

or

```html
<strong>Bold Text</strong>
```

---

### Italic

```html
<i>Italic Text</i>
```

or

```html
<em>Italic Text</em>
```

---

### Underline

```html
<u>Underline</u>
```

---

### Mark

```html
<mark>Highlighted Text</mark>
```

---

### Small

```html
<small>Small Text</small>
```

---

### Delete

```html
<del>Deleted Text</del>
```

---

### Insert

```html
<ins>Inserted Text</ins>
```

---

### Superscript

```html
x<sup>2</sup>
```

---

### Subscript

```html
H<sub>2</sub>O
```

---

# Links

```html
<a href="https://google.com">Visit Google</a>
```

Open in new tab:

```html
<a href="https://google.com" target="_blank">
Google
</a>
```

---

# Images

```html
<img src="image.jpg" alt="Profile Image">
```

With width and height

```html
<img src="image.jpg"
     width="200"
     height="200">
```

---

# Lists

## Ordered List

```html
<ol>
    <li>Java</li>
    <li>Python</li>
    <li>JavaScript</li>
</ol>
```

---

## Unordered List

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

---

# Tables

```html
<table border="1">

<tr>
<th>Name</th>
<th>Age</th>
</tr>

<tr>
<td>Hemanth</td>
<td>21</td>
</tr>

</table>
```

---

# Forms

## Input

```html
<input type="text">
```

Common Types

```html
text
password
email
number
date
file
checkbox
radio
submit
```

---

## Label

```html
<label>Name</label>
```

---

## Button

```html
<button>Click Me</button>
```

---

## Textarea

```html
<textarea></textarea>
```

---

## Select

```html
<select>

<option>Mysore</option>

<option>Bangalore</option>

</select>
```

---

# Div

```html
<div>

Content goes here

</div>
```

Used for grouping elements.

---

# Span

```html
<span>Inline Content</span>
```

Used for styling part of a sentence.

---

# Semantic Tags

| Tag | Purpose |
|------|----------|
| `<header>` | Top section |
| `<nav>` | Navigation |
| `<section>` | Section |
| `<article>` | Article |
| `<aside>` | Sidebar |
| `<footer>` | Footer |

Example

```html
<header>

Website Header

</header>

<section>

Main Content

</section>

<footer>

Copyright 2026

</footer>
```

---

# Multimedia

## Audio

```html
<audio controls>

<source src="song.mp3">

</audio>
```

---

## Video

```html
<video controls width="400">

<source src="video.mp4">

</video>
```

---

# HTML Entities

| Entity | Output |
|---------|--------|
| `&lt;` | < |
| `&gt;` | > |
| `&amp;` | & |
| `&copy;` | © |
| `&nbsp;` | Space |

---

# Important Attributes

| Attribute | Purpose |
|------------|----------|
| id | Unique identifier |
| class | Group elements |
| href | Link URL |
| src | Image source |
| alt | Alternate text |
| width | Width |
| height | Height |
| target | Open link in new tab |
| type | Input type |
| value | Default value |
| placeholder | Hint text |

---

# Student Profile Assignment

## Objective

Create a simple Student Profile webpage using only HTML.

---

## Requirements

Your webpage should contain:

### 1. Title

```
Student Profile
```

---

### 2. Main Heading

Display your name using:

```html
<h1>
```

---

### 3. Personal Information

Use paragraphs to display:

- Name
- Age
- Branch
- College
- Semester

---

### 4. Profile Picture

Display your image using:

```html
<img>
```

---

### 5. About Me

Write a short paragraph (5–6 lines).

---

### 6. Skills

Create an unordered list containing at least five skills.

Example:

- Java
- HTML
- CSS
- JavaScript
- MySQL

---

### 7. Hobbies

Create an ordered list.

---

### 8. Education Table

Include:

| Qualification | Institution | Percentage/CGPA |
|---------------|-------------|-----------------|
| SSLC | | |
| PUC | | |
| Degree | | |

---

### 9. Contact Form

Include:

- Name
- Email
- Phone
- Gender
- Branch
- Feedback
- Submit Button

---

### 10. Favorite Website

Create a hyperlink to your favorite website.

Example:

Google

GitHub

YouTube

---

### 11. Footer

Display:

```
© 2026 Your Name
```

---

# Submission Instructions

- File name should be:

```
student_profile.html
```

- Write clean and properly indented HTML.
- Use meaningful headings.
- Complete all the required sections.
- Do not use CSS or JavaScript.
- Submit before the deadline.

---

---

# Practice Daily

The best way to learn HTML is by building small webpages every day.
# study plan of the HTML 

The best possible way is to learn it using the mdn.docs official platform 
Happy Coding!
