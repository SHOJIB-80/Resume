# 🎯 Professional Resume Website

A modern, fully responsive resume website showcasing professional experience, skills, and projects.

---

## 📋 Overview

This is a professionally designed personal resume website featuring:
- ✨ Modern, clean interface with dark/light theme support
- 📱 Fully responsive design for all devices
- 🎨 Interactive animations and smooth transitions
- 📄 ATS-friendly one-page resume (printable PDF)
- 📧 Contact form integration
- 🌐 Deployment-ready

---

## 📂 Project Structure

```
Resume/
├── index.html              # Main portfolio website
├── resume.html             # One-page printable/ATS resume
├── style.css               # Styling (dark/light theme, animations)
├── script.js               # Interactive features
├── resume.pdf              # Downloadable resume (PDF export)
├── LICENSE                 # Copyright & usage restrictions
└── README.md               # This file

Optional:
assets/
├── photo.jpg               # Profile photo
└── projects/
    ├── project1.jpg
    └── project2.jpg
```

---

## 🚀 Getting Started

### 1. **Customize Your Information**
All customization points are marked with `<!-- Replace` comments in `index.html`:

- **Name & Title**: Update in hero section
- **Contact Information**: Update email, LinkedIn, GitHub, portfolio links
- **Profile Photo**: Replace with your headshot
- **Projects**: Add your portfolio projects with live/GitHub links
- **Testimonials**: Update client/colleague feedback
- **Skills**: Customize technical and soft skills

### 2. **Add Your Photo**
1. Save your professional headshot as `assets/photo.jpg`
2. Update the image path in the HTML

### 3. **Export Resume as PDF**
1. Open `resume.html` in **Google Chrome**
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Save as PDF with margins set to "None"

### 4. **Connect Your Contact Form**
Choose one option:

**Option A — Formspree (Recommended):**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

**Option B — EmailJS:**
Visit https://emailjs.com and configure in `script.js`

---

## 🎨 Theme Customization

Edit the CSS variables in `style.css` (`:root` section):
```css
--accent: #63b3ed;        /* Primary accent color */
--accent-warm: #f6ad55;   /* Warm accent */
--accent-purple: #b794f4; /* Purple accent */
--accent-green: #68d391;  /* Success/positive color */
```

---

## 🌍 Deployment

### **Netlify (Recommended)**
```bash
git init
git add .
git commit -m "Deploy resume website"
git remote add origin https://github.com/YOUR_USERNAME/Resume.git
git push -u origin main
```
Then connect your repo on [Netlify.com](https://netlify.com)

### **Vercel**
Connect your GitHub repo on [Vercel.com](https://vercel.com)

### **GitHub Pages**
Push to `main` branch and enable Pages in repository settings.

---

## 📊 Tech Stack

- **HTML5** — Semantic markup, ATS-optimized
- **CSS3** — Modern styling, animations, glassmorphism effects
- **JavaScript (Vanilla)** — Interactive features, no dependencies
- **Google Fonts** — Professional typography
- **Font Awesome** — Icons

---

## ⚡ Performance Optimization

- Compress images: Use [Squoosh.app](https://squoosh.app) (target < 200KB)
- Run Lighthouse audit after deployment
- Enable lazy loading for project images
- Minify CSS/JS before production deployment

---

## 📝 License

**All Rights Reserved** — See [LICENSE](LICENSE) file for details.

This resume website and all its contents are protected by copyright. Unauthorized copying, reproduction, or distribution is strictly prohibited.

---

## 📞 Support

For issues or questions about the website, please open an issue in the repository.

---

**Built with:** HTML5 · CSS3 · Vanilla JavaScript · Google Fonts · Font Awesome

Made with ❤️ by Sirajul Islam
