# Vaishnav N — Portfolio Website

A futuristic dark-themed AI portfolio website built for GitHub Pages hosting.

## 🚀 Quick Start

1. Upload this entire folder to a GitHub repository named exactly: `Vaishnav17-2004.github.io`
2. Go to **Settings → Pages → Branch: main → / (root)** and save.
3. Your site will be live at: `https://Vaishnav17-2004.github.io`

---

## 📁 Folder Structure

```
vaishnav-portfolio/
│
├── index.html          ← Main HTML (edit content here)
├── README.md           ← This file
│
├── css/
│   ├── style.css       ← All styles — colors, layout, animations
│   └── README.md       ← CSS editing guide
│
├── js/
│   ├── main.js         ← Interactions: typed text, scroll, filter, nav
│   ├── particles.js    ← Neural background particle animation
│   └── README.md       ← JS editing guide
│
├── images/
│   ├── profile.jpg     ← ⚠️ ADD YOUR PHOTO HERE (any square image)
│   └── README.md       ← Image guide
│
└── assets/
    ├── Vaishnav_CV.pdf ← ⚠️ ADD YOUR RESUME HERE
    └── README.md       ← Assets guide
```

---

## ✏️ Key Editing Guide

### Change Your Name / Title
Open `index.html` and find:
```html
<span class="line1">VAISHNAV</span>
<span class="line2">N</span>
```
Edit these to your name.

### Change Typed Text Phrases
Open `js/main.js`, find `const phrases` and edit the array:
```js
const phrases = [
  'Data Scientist',
  'ML Engineer',
  ...
];
```

### Add Your Profile Photo
Drop your photo as `images/profile.jpg`.
- Recommended: Square, minimum 400×400px
- Formats: JPG, PNG, WebP

### Update Resume Link
Place your PDF at `assets/Vaishnav_CV.pdf`
(already linked in the Resume button and nav)

### Add/Edit Projects
In `index.html`, find `<div class="projects-grid">` and copy any `project-card` block:
```html
<div class="project-card" data-category="ml">
  <div class="card-num">09</div>
  <div class="card-icon"><i class="fas fa-chart-bar"></i></div>
  <h3 class="card-title">Your Project Title</h3>
  <p class="card-desc">Your description here.</p>
  <div class="card-tags"><span>Python</span><span>ML</span></div>
  <div class="card-links">
    <a href="YOUR_GITHUB_URL" target="_blank"><i class="fab fa-github"></i> Code</a>
  </div>
</div>
```
`data-category` options: `ml`, `nlp`, `viz`, `other`

### Update Social Links
Search for `https://github.com/Vaishnav17-2004` and replace throughout `index.html`.
Search for `vaishnavvichu216@gmail.com` and replace with your email.

### Change Colors
Open `css/style.css`, at the top find `:root { ... }` and edit:
- `--accent` → main cyan color (default `#00d4ff`)
- `--accent2` → purple accent (default `#7b2fff`)
- `--accent3` → pink accent (default `#ff3d6e`)
- `--bg` → background (default `#020510`)

---

## 🌐 GitHub Pages Deployment

1. Create a new repo on GitHub: `YOUR_USERNAME.github.io`
2. Upload all files (keep folder structure intact)
3. Go to repo **Settings → Pages**
4. Set Source: **Deploy from a branch → main → / (root)**
5. Click **Save** — live in ~1 minute

### Alternative: Any Repo Name
If using a different repo name (e.g., `portfolio`), your URL will be:
`https://Vaishnav17-2004.github.io/portfolio/`

---

## 🎨 Fonts Used
- **Orbitron** — Display headings (via Google Fonts)
- **Syne** — Body text (via Google Fonts)
- **JetBrains Mono** — Code/labels (via Google Fonts)

## 📦 Icons
Font Awesome 6.5 (loaded via CDN) — no local files needed.

---

## 📝 License
Free to use and customize for personal portfolio use.
