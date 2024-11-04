Here's a simple example of an HTML document linked to a CSS file, using IDs, classes, and tags. I'll also include a few challenges for students to practice using CSS selectors.

---

### 1. HTML Document (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Selectors Practice</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header id="main-header">
    <h1>Welcome to CSS Selectors Practice</h1>
    <p class="subtitle">Learn how to use IDs, classes, and tags with CSS.</p>
  </header>

  <section class="content">
    <article id="intro">
      <h2>Introduction</h2>
      <p>This section introduces basic concepts for using CSS selectors to style HTML.</p>
    </article>

    <article id="examples">
      <h2>Examples</h2>
      <p class="highlight">Use different selectors to change the appearance of this text.</p>
      <p class="highlight">Try styling elements based on IDs, classes, and tags.</p>
    </article>

    <footer id="main-footer">
      <p>&copy; 2024 CSS Practice</p>
      <p class="footer-link">Learn more about CSS on <a href="https://www.w3schools.com/css/">W3Schools</a>.</p>
    </footer>
  </section>
</body>
</html>
```

### 2. CSS File (styles.css)

```css
/* Tag selector */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f0f0f5;
}

/* ID selectors */
#main-header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

#intro {
  background-color: #e6f7ff;
  padding: 15px;
  border-left: 5px solid #0099cc;
}

#examples {
  background-color: #e6ffe6;
  padding: 15px;
  border-left: 5px solid #33cc33;
}

/* Class selectors */
.subtitle {
  font-size: 1.2em;
  color: #666;
}

.highlight {
  font-weight: bold;
  color: #005580;
}

/* Element selector */
footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
}

.footer-link {
  color: #ffa500;
  text-decoration: none;
}

/* Tag selector with class */
a:hover {
  color: #ff4500;
}
```

---

### Challenges

1. **ID and Class Styling**:  
   - Change the background color of `#main-header` to a different shade and the text color of `.subtitle` to a contrasting color.
   - Modify the font size of `.highlight` to make it more noticeable.

2. **Tag and Class Combination**:
   - Create a new class `.centered-text` and apply it to paragraphs in `#examples` to center-align the text.
   - Add padding to the footer links and change the hover color of links.

3. **Styling Tags with Multiple Classes**:
   - Add another article section with different `id` and `class` attributes and style it using CSS rules that combine tags, classes, and IDs.
