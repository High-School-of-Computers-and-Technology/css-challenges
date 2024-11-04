Please create an index.html file and a style.css file as described below

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


### CSS Challenges

1. **Customize Header and Footer Colors**  
   - Change the background color and text color of the `#main-header` and `#main-footer`. Choose colors that contrast well with each other and the body background.

2. **Add Borders and Padding**  
   - Add a border around each `article` section (`#intro` and `#examples`). Adjust the border thickness, style (solid, dotted, dashed), and color.
   - Add padding inside each section to ensure the text does not touch the borders.

3. **Modify Font Properties**  
   - Change the font size and style of the `h2` tags within each `article` section.
   - Set the font for `.subtitle` to a different font family from the rest of the page and adjust its size and color.

4. **Background Colors for Classes**  
   - Add a light background color to all paragraphs with the `.highlight` class.
   - Try using RGBA values (e.g., `rgba(0, 0, 0, 0.1)`) to make the background semi-transparent.

5. **Hover Effects on Links**  
   - Modify the link styling in the footer so that links have different colors on hover and active states.
   - Add an underline effect on hover to emphasize links in `.footer-link`.

6. **Experiment with Margins and Spacing**  
   - Adjust the `margin` around each `article` section to add space between them.
   - Center the entire `section` element on the page by adding `margin: auto` and setting a `max-width` (e.g., `600px`).

7. **Style Based on Hierarchy**  
   - Add styling to make only the first paragraph inside `#examples` bold.
   - Try selecting the `p` tags only within `#intro` and give them a distinct color or font style.

8. **Use `nth-child` Selectors**  
   - Style every second paragraph with the `.highlight` class in `#examples` using the `nth-child` selector.
   - Experiment with other `nth-child` patterns to alternate background colors between different elements.

9. **Text Alignment and Shadow Effects**  
   - Center-align the text in `#main-header` and add a subtle shadow effect.
   - Add a shadow to the text in each `h2` tag, making it stand out against the background.

10. **Transform and Transition Effects**  
    - Add a transition effect on the `.footer-link` so that the color changes smoothly when hovered.
    - Apply a slight rotation or scale effect on the `h1` title in `#main-header` when the user hovers over it to make it pop.

---

Each of these challenges will give you a chance to explore CSS styling techniques, work with various selectors, and learn more about styling for layout and interactivity! Let me know if you'd like examples of any of these.
