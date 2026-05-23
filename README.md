# Sirajul Islam — Resume Website

A premium, ATS-friendly personal resume website + downloadable one-page resume.

---

## Folder Structure

```
sirajul-resume/
├── index.html      ← Main portfolio website (all 8 sections)
├── style.css       ← All styles (dark/light theme, glassmorphism, animations)
├── script.js       ← All JavaScript (cursor, loader, reveals, form, etc.)
├── resume.html     ← One-page printable/ATS resume (export to PDF here)
├── resume.pdf      ← Your exported PDF resume
└── README.md       ← This file
```

Optional folders to create:
```
assets/
├── photo.jpg       ← Your headshot 
└── projects/       ← Project screenshots
    ├── master.jpg
    └── demandiq.jpg
```

---

## How to Edit Content

### 1. Your Name, Title, Tagline
Search for `<!-- Replace` in `index.html` — every customization point is marked.

Key locations:
- **Line ~19**: `<title>` tag — page title for SEO
- **Line ~52**: `.nav-logo` — initials "SI."
- **Hero section**: name, title tagline, stats
- **Footer**: name, copyright year

### 2. Your Photo
Find this comment in `index.html`:
```html
<!-- Replace this entire block with: <img src="photo.jpg" alt="Sirajul Islam" /> -->
```
Replace the entire `<div class="placeholder-inner">...</div>` with:
```html
<img src="assets/photo.jpg" alt="Sirajul Islam" style="width:100%;height:100%;object-fit:cover;border-radius:inherit;" />
```

### 3. Contact Links (replace all `href="#"` and placeholder emails/URLs)
- Email: search `sirajul@email.com`
- LinkedIn: search `linkedin.com/in/sirajul`
- GitHub: search `github.com/sirajul`
- Upwork: search `upwork.com/freelancers/sirajul`
- Portfolio URL: search `sirajul.dev`

### 4. Resume PDF
- Export `resume.html` to PDF (instructions below)
- Save as `resume.pdf` in the root folder
- The "Download Resume" buttons already point to `resume.pdf`

### 5. Projects
Each project card in `index.html` has:
```html
<!-- Replace with actual project URLs -->
<a href="#" ...>Live</a>
<a href="#" ...>GitHub</a>
```
Replace `#` with your actual URLs.

### 6. Testimonials
Replace the placeholder client names, companies, and quotes in the Testimonials section.

### 7. Contact Form
The form is currently mocked. To make it real:

**Option A — Formspree (easiest):**
1. Go to https://formspree.io, create a free account
2. Create a form, get your form ID (e.g. `xrgbkpqz`)
3. Change the form submission handler in `script.js` or add `action` attribute:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

**Option B — EmailJS:**
1. Go to https://emailjs.com
2. Follow their setup, replace the mock submit handler in `script.js`

**Option C — Netlify Forms:**
Add `netlify` attribute to the form tag and deploy on Netlify.

---

## How to Export the One-Page PDF Resume

1. Open `resume.html` in **Google Chrome**
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Set destination to **"Save as PDF"**
4. Set margins to **"None"** or **"Minimum"**
5. Make sure **"Background graphics"** is checked
6. Click **Save**
7. Save as `resume.pdf` in the project root

The resume is already ATS-optimized:
- Semantic HTML tags (`h1`, `h3`, `ul`, `strong`)
- No images in text areas
- All text is selectable/copyable
- Clean hierarchy for parsers

---

## Deploy on Netlify

1. Push your folder to GitHub:
```bash
git init
git add .
git commit -m "Initial commit: resume website"
git remote add origin https://github.com/YOUR_USERNAME/sirajul-resume.git
git push -u origin main
```

2. Go to https://netlify.com → "New site from Git"
3. Connect your GitHub repo
4. Build settings: leave blank (static site)
5. Click **Deploy**

**Custom domain:** Netlify Settings → Domain Management → Add custom domain (e.g. `sirajul.dev`)

---

## Deploy on Vercel

1. Push to GitHub (same as above)
2. Go to https://vercel.com → "New Project" → Import from GitHub
3. Framework preset: **Other**
4. Click **Deploy**

---

## Theme Customization

All colors are CSS variables in `style.css` `:root` block:
```css
--accent:       #63b3ed;   /* Main blue — change to your brand color */
--accent-warm:  #f6ad55;   /* Gold/amber accent */
--accent-purple:#b794f4;   /* Purple accent */
--accent-green: #68d391;   /* Green (success, "open to work") */
```

---

## Performance Tips

- Compress your photo: use https://squoosh.app (target < 200KB)
- Run Lighthouse audit after deploy: Chrome DevTools → Lighthouse
- Add `loading="lazy"` to project screenshot images

---

Built with: HTML5 · CSS3 · Vanilla JS · Google Fonts · Font Awesome
