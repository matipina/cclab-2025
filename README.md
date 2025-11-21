# Simple p5.js Portfolio Template

A beginner-friendly HTML template for showcasing your p5.js creative coding projects.

## 🎯 Learning Objectives

By completing this project, you will:

- Understand HTML document structure and semantic elements
- Learn how to integrate p5.js sketches into a webpage
- Practice using HTML tags like `<header>`, `<nav>`, `<section>`, and `<footer>`
- Create a simple portfolio to showcase your creative coding work

## 📁 Project Structure

```
cclab-2025/
├── index.html               # Main HTML file with portfolio structure
├── styles.css               # CSS styling for the portfolio
├── intro-to-html.md         # HTML reference guide
├── p5-integration-guide.md  # Guide for adding p5.js sketches
├── emmet-cheatsheet.md      # Quick Emmet reference
├── images/                  # Folder for your images
└── README.md                # This file
```

## 🚀 Getting Started

### Option 1: Open with Live Server (Recommended)

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Your browser will open and automatically reload when you save changes!

### Option 2: Open Directly in Browser

1. Find `index.html` in your file system
2. Double-click it to open in your default browser
3. Manually refresh the page (Cmd+R / Ctrl+R) after making changes

## ✨ Using Emmet in VS Code

Emmet is built into VS Code and makes writing HTML/CSS much faster!

### Essential Emmet Shortcuts

| Type this | Press Tab | Get this |
|-----------|-----------|----------|
| `!` | Tab | Full HTML5 boilerplate |
| `html:5` | Tab | Full HTML5 boilerplate |
| `.container` | Tab | `<div class="container"></div>` |
| `#header` | Tab | `<div id="header"></div>` |
| `section.hero` | Tab | `<section class="hero"></section>` |
| `ul>li*3` | Tab | `<ul>` with 3 `<li>` children |
| `nav>ul>li*4>a` | Tab | Navigation menu structure |
| `.card>.title+.content` | Tab | Card with title and content divs |

### Emmet Tips

- **Enable Tab expansion**: Go to VS Code settings and search for "emmet trigger" or add to `settings.json`:

  ```json
  {
    "emmet.triggerExpansionOnTab": true
  }
  ```

- **Alternative to Tab**: Press `Ctrl+Space` to show Emmet suggestions, then `Enter`
- **Cheat sheet**: [Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/)

## 📝 Customization Checklist

Make this portfolio your own! Follow these steps:

### Step 1: Update Content

- [ ] Change "Your Name" to your actual name (in header and hero section)
- [ ] Write your own bio in the About section
- [ ] Update contact links (email and GitHub)

### Step 2: Customize the p5.js Sketch

- [ ] Open `index.html` and scroll to the `<script>` section at the bottom
- [ ] Experiment with the p5.js code - change colors, shapes, or behavior
- [ ] Try making the sketch respond to clicks or keypresses
- [ ] Replace with your own p5.js sketch code!

### Step 3: Expand (Optional)

- [ ] Add more sketches using p5.js instance mode (see `p5-integration-guide.md`)
- [ ] Customize colors and fonts in `styles.css`
- [ ] Add a description or instructions for your sketch
- [ ] Link to your sketch on the p5.js web editor

## 📚 Key HTML Concepts Covered

### Semantic HTML Elements

- **`<header>`**: Contains site branding and navigation
- **`<nav>`**: Navigation menu with links
- **`<main>`**: Primary content of the page
- **`<section>`**: Thematic grouping of content (About, Projects, Contact)
- **`<article>`**: Self-contained content (each project card)
- **`<footer>`**: Bottom information and copyright

### Other Important HTML

- **Links**: Internal (`#about`) and external (`https://...`) links with `<a>` tags
- **Images**: Using `<img>` with `src` and `alt` attributes
- **Lists**: Using `<ul>` and `<li>` for navigation
- **Headings**: `<h1>`, `<h2>`, `<h3>` for document hierarchy
- **Paragraphs**: `<p>` for text content
- **Divs**: `<div>` for grouping content
- **Scripts**: Using `<script>` to add JavaScript and p5.js interactivity

### Why Semantic HTML Matters

Using the right HTML tags (semantic HTML) helps:

- Screen readers understand your content (accessibility)
- Search engines index your site better (SEO)
- Other developers read your code more easily
- You organize your thoughts and content structure

### Adding Interactivity with p5.js

This template includes a working p5.js sketch that demonstrates:

- How to include external JavaScript libraries via CDN
- How to place a canvas in a specific HTML element
- Basic p5.js setup and draw functions
- Mouse interaction in creative coding

Check out `p5-integration-guide.md` for detailed instructions on working with p5.js!

## 🐛 Common Issues & Solutions

### Problem: Emmet not working

**Solution**: Make sure your file is saved as `.html`, and try `Ctrl+Space` then `Enter` instead of Tab

### Problem: Styles not loading

**Solution**: Check that `styles.css` is in the same folder as `index.html`, and the `<link>` tag in the `<head>` is correct

### Problem: Images not showing

**Solution**: Make sure image files are in the `images/` folder and filenames match exactly (including file extensions)

### Problem: Something looks wrong

**Solution**: Check your HTML tags - make sure every opening tag has a closing tag (like `<section>` and `</section>`)

## 🔗 Helpful Resources

- [MDN HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
- [MDN CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps)
- [W3Schools](https://www.w3schools.com/)
- [CSS-Tricks](https://css-tricks.com/)
- [Can I Use](https://caniuse.com/) - Check browser support for CSS features

## 🎓 Next Steps

Once you're comfortable with this template:

1. Deploy your site using [GitHub Pages](https://pages.github.com/) or [Netlify](https://www.netlify.com/)
2. Learn JavaScript to add interactivity
3. Explore CSS frameworks like Tailwind or Bootstrap
4. Try building a multi-page website
5. Learn about web accessibility (a11y) best practices

## 📬 Questions?

Ask your instructor during class or office hours!

---

**Happy coding!** 🚀
