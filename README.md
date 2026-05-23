# 🎯 Sirajul Islam — Professional Resume Website

Welcome to my modern, fully-featured professional resume website. This is a production-ready portfolio designed to showcase your professional identity.

---

## 📖 About This Repository

This repository contains a complete, professional resume website with:
- 🌐 Interactive portfolio website
- 📄 ATS-friendly one-page resume (PDF export)
- 🎨 Modern design with dark/light theme
- 📱 Fully responsive (desktop, tablet, mobile)
- ✨ Smooth animations and transitions
- 📧 Contact form integration
- 🚀 Deploy-ready to Netlify, Vercel, or GitHub Pages

**Perfect for:** Professionals, freelancers, developers, designers, and anyone looking to showcase their work with a polished, modern resume website.

---

## 🚀 Quick Start Guide

### Step 1: Download/Clone This Repository
```bash
git clone https://github.com/SHOJIB-80/Resume.git
cd Resume
```

### Step 2: Customize Your Information
Open `index.html` in your text editor and find all sections marked with `<!-- Replace`:

1. **Your Name & Title** (Hero Section)
   - Line ~50: Update your name
   - Line ~52: Update your professional title
   - Line ~54: Update your tagline

2. **Contact Information**
   - Search for `sirajul@email.com` → Replace with your email
   - Search for `linkedin.com/in/sirajul` → Replace with your LinkedIn
   - Search for `github.com/sirajul` → Replace with your GitHub
   - Search for `upwork.com/freelancers/sirajul` → Replace with your Upwork profile

3. **Add Your Photo**
   - Save your professional headshot as `assets/photo.jpg`
   - Update the image path in the HTML

4. **Add Your Projects**
   - Update project titles, descriptions, images, and links in the Projects section

5. **Add Your Experience & Skills**
   - Update your work experience timeline
   - List your technical and soft skills
   - Add your certifications

6. **Testimonials** (Optional)
   - Replace placeholder client names, companies, and quotes

### Step 3: Create Your Resume PDF
1. Open `resume.html` in **Google Chrome**
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Click **Save as PDF** with these settings:
   - Margins: **None** or **Minimum**
   - Check **Background graphics**
4. Save as `resume.pdf` in the project root

### Step 4: Setup Contact Form (Optional)
Choose one service:

**Formspree (Easiest):**
- Go to https://formspree.io
- Create a free form and get your Form ID
- In `index.html`, find the form and update:
  ```html
  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  ```

### Step 5: Deploy Your Website
Choose your preferred platform:

**🌐 Netlify:**
1. Push to GitHub (if not already)
2. Go to https://netlify.com
3. Click "New site from Git"
4. Connect your GitHub repo → Deploy

**🔧 Vercel:**
1. Go to https://vercel.com
2. Click "New Project" → Import from GitHub
3. Select your repo → Deploy

**📌 GitHub Pages:**
1. Go to repository Settings → Pages
2. Select `main` branch as source
3. Your site is live at `https://SHOJIB-80.github.io/Resume`

---

## ✨ Special Features & Advantages

### 🎨 **Beautiful Design**
- Modern glassmorphism effects
- Smooth animations and transitions
- Professional color scheme (customizable)
- Dark and light theme support
- Fully responsive on all devices

### 📱 **Mobile-First Approach**
- Works perfectly on smartphones, tablets, and desktops
- Touch-friendly navigation
- Optimized performance for mobile devices

### 📄 **ATS-Optimized Resume**
- Semantic HTML structure for easy parsing
- All text is selectable and copyable
- No images in content areas
- Printer-friendly format
- Compatible with Applicant Tracking Systems

### ⚡ **High Performance**
- No external frameworks or dependencies
- Pure HTML5, CSS3, and Vanilla JavaScript
- Lightweight and fast loading
- Optimized images and assets
- Excellent Lighthouse scores

### 🎯 **Easy to Customize**
- All customization points clearly marked with comments
- No coding knowledge required for basic edits
- Change colors, fonts, and content easily
- Modular structure for adding new sections

### 🔐 **Professional & Secure**
- Clean, professional code
- Copyright protected
- GDPR-friendly contact form options
- No tracking or ads

### 📊 **Complete Package**
- Includes portfolio website AND resume PDF
- One-page resume format
- Skills showcase section
- Project portfolio section
- Testimonials section
- Call-to-action buttons throughout

### 🌐 **Search Engine Optimized (SEO)**
- Proper meta tags
- Semantic HTML structure
- Open Graph tags for social sharing
- Fast load times improve rankings

---

## 📁 File Structure

```
Resume/
├── index.html              # Main portfolio website
├── resume.html             # One-page printable resume
├── style.css               # All styling & animations
├── script.js               # Interactive features
├── resume.pdf              # Your downloadable resume
├── LICENSE                 # Copyright protection
├── README.md               # This file
└── assets/                 # (Create this folder)
    ├── photo.jpg           # Your profile photo
    └── projects/           # Project screenshots
        ├── project1.jpg
        └── project2.jpg
```

---

## 🎨 Customization Options

### Change Colors
Open `style.css` and find the `:root` section:
```css
--accent: #63b3ed;        /* Primary color (blue) */
--accent-warm: #f6ad55;   /* Warm accent (orange) */
--accent-purple: #b794f4; /* Purple accent */
--accent-green: #68d391;  /* Success color (green) */
```

### Change Fonts
Search for `Google Fonts` in `index.html` to update typography.

### Add New Sections
Use existing sections as templates and duplicate them with your content.

---

## 🔒 License

**All Rights Reserved** — This work is protected by copyright law.

**What you CAN do:**
✅ Use this template for your personal portfolio  
✅ Download and customize it with your information  
✅ Deploy it online to showcase your work  

**What you CANNOT do:**
❌ Copy/clone this design for others  
❌ Use it as a template for clients/reselling  
❌ Redistribute the code or design  
❌ Create derivative works without permission  

**For permissions or licensing inquiries:**
📧 Email: sirajul@email.com

See the [LICENSE](LICENSE) file for complete legal terms.

---

## 🆘 Troubleshooting

**Images not showing?**
- Check that image paths are correct in HTML
- Ensure images are in the `assets/` folder

**Form not working?**
- Make sure you've set up Formspree or EmailJS
- Check that the form action URL is correct

**Resume PDF looks wrong?**
- Use Google Chrome to export
- Set margins to "None" or "Minimum"
- Make sure "Background graphics" is checked

**Website not deploying?**
- Ensure your repo is public
- Check deployment platform settings
- Verify all file paths are relative (not absolute)

---

## 📚 Resources

- [Google Fonts](https://fonts.google.com) — Free fonts
- [Font Awesome](https://fontawesome.com) — Icons
- [Formspree](https://formspree.io) — Contact forms
- [Netlify](https://netlify.com) — Web hosting
- [Vercel](https://vercel.com) — Web hosting

---

## 📞 Support

Found a bug or have a question? [Open an issue](https://github.com/SHOJIB-80/Resume/issues) on GitHub.

---

## 🎓 Credits

**Built with:**
- HTML5 — Semantic markup
- CSS3 — Modern styling & animations
- Vanilla JavaScript — No dependencies
- Google Fonts — Professional typography
- Font Awesome — Beautiful icons

**Author:** Sirajul Islam  
**Repository:** [github.com/SHOJIB-80/Resume](https://github.com/SHOJIB-80/Resume)

---

Made with ❤️ to help you showcase your professional journey.
