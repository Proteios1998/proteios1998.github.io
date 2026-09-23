# My Personal Academic Page

## File structure

```
my-site/
├── index.html   ← your content lives here — this is the file you edit
├── style.css    ← all visual styling (colors, fonts, layout)
├── README.md    ← this guide
└── photo.jpg    ← add your photo here (any name works, update index.html to match)
```

## How to edit

Open `index.html` in any text editor. Each section has a comment block like:

```html
<!-- ============================================================
  ABOUT
  ...
============================================================ -->
```

Follow the instructions in the comment to update that section.

### Quick reference

| What to change | Where in index.html |
|---|---|
| Name in browser tab | `<title>` in `<head>` |
| Name in nav | `<a href="#about" class="name">` |
| Name, title, institution | Inside `#about` section |
| Bio paragraphs | The two `<p>` tags in `.hero-text` |
| Photo | Replace `<div class="avatar">` with `<img src="photo.jpg">` |
| Social / profile links | `.links` block in `#about` |
| Add a publication | Duplicate a `<li class="pub-item">` in `#publications` |
| Add a project card | Duplicate a `<div class="project-card">` in `#projects` |
| Add a CV entry | Duplicate a `<div class="cv-item">` in `#cv` |
| Footer year / name | `<footer>` at the bottom |

### Customizing colors or fonts

Open `style.css` and edit the variables at the top of the file:

```css
:root {
  --accent: #2c5f8a;   /* main color (links, tags, hover) */
  --bg: #f7f6f3;       /* page background */
  --serif: 'EB Garamond', Georgia, serif;   /* headings font */
  --sans: 'Inter', system-ui, sans-serif;   /* body font */
}
```

## How to preview locally

Open `index.html` directly in your browser — no server needed.

## How to publish (GitHub Pages)

1. Create a GitHub repository named `yourusername.github.io`
2. Upload all files in this folder to that repo
3. Your site will be live at `https://yourusername.github.io`
# ziqingpan.github.io
