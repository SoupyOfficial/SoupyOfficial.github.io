# Personal Portfolio Site

A clean, modern, responsive portfolio site designed for NFC business card integration and optimized for GitHub Pages deployment.

## 🌟 Features

- **Modern Design**: Clean, responsive layout with dark theme
- **NFC-Ready**: Optimized for NFC business card integration
- **Contact Card**: Downloadable vCard (.vcf) for easy contact saving
- **SEO Optimized**: Meta tags, OpenGraph, and JSON-LD structured data
- **GitHub Pages Ready**: Zero-config deployment
- **Single File**: Self-contained HTML with inlined CSS and JavaScript

## 🚀 Quick Start

1. **Personalize the content**: Edit `index.html` and replace all placeholder content marked with `TODO:` comments
2. **Replace assets**: 
   - `avatar.jpg` - Your profile photo
   - `resume.pdf` - Your resume
   - `og-card.png` - OpenGraph preview image
   - Favicon files (`favicon.ico`, `favicon.svg`, `apple-touch-icon.png`)
3. **Commit and push** - GitHub Pages will automatically deploy from the main branch

## 📝 Customization Guide

### Essential Updates

Search for `TODO:` comments in `index.html` and replace:

1. **Personal Information**
   - Name and title in `<title>` and header
   - Bio in the About section
   - Skills chips and technologies

2. **Contact Details**
   - Email address (multiple locations)
   - LinkedIn profile URL
   - Phone number in the vCard
   - Address in the vCard

3. **Projects Section**
   - Replace with your actual GitHub repositories
   - Update project names, descriptions, and technologies
   - Add/remove projects as needed

4. **Social Links**
   - GitHub username (already set to SoupyOfficial)
   - LinkedIn profile
   - Calendly link (optional)

5. **Assets**
   - Replace `avatar.jpg` with your professional photo (96x96px recommended)
   - Update `resume.pdf` with your actual resume
   - Replace `og-card.png` with a custom preview image (1200x630px)

### Advanced Customization

- **Colors**: Modify CSS custom properties in the `:root` section
- **Fonts**: Update the font stack in the `body` CSS rule
- **Layout**: Adjust grid layouts and spacing in the CSS
- **Add sections**: Follow the existing card structure pattern

## 📱 NFC Business Card Integration

This site is optimized for NFC business cards. Simply program your NFC card to point to:
```
https://SoupyOfficial.github.io/
```

When someone taps your card, they'll see your portfolio and can easily:
- Save your contact info (vCard download)
- View your projects and skills
- Access your resume and social links

## 🔧 Technical Details

- **Tech Stack**: Pure HTML, CSS, and JavaScript
- **Hosting**: GitHub Pages (free)
- **Performance**: Single file, minimal external dependencies
- **Accessibility**: Semantic HTML, focus management, ARIA labels
- **SEO**: Meta tags, OpenGraph, Twitter Cards, JSON-LD schema

## 📦 Deployment

### GitHub Pages (Automatic)
1. Push to the `main` branch
2. Go to Settings > Pages in your GitHub repository
3. Select "Deploy from a branch" and choose `main`
4. Your site will be available at `https://SoupyOfficial.github.io/`

### Local Development
```bash
# Serve locally (Python 3)
python -m http.server 8000

# Or with Node.js
npx serve .

# Then open http://localhost:8000
```

## 🎨 Design Philosophy

- **Clean**: Minimal distractions, focus on content
- **Modern**: Contemporary design patterns and typography
- **Responsive**: Works perfectly on mobile and desktop
- **Accessible**: High contrast, keyboard navigation, screen reader friendly
- **Fast**: Single file, optimized loading, minimal dependencies

## 📄 File Structure

```
.
├── index.html          # Main portfolio page
├── avatar.jpg          # Profile photo (replace with yours)
├── resume.pdf          # Resume PDF (replace with yours)
├── og-card.png         # OpenGraph preview image
├── favicon.ico         # Browser favicon
├── favicon.svg         # Modern SVG favicon
├── apple-touch-icon.png # iOS home screen icon
├── manifest.json       # Web app manifest
└── README.md          # This file
```

## 🤝 Contributing

This is a personal portfolio template. Feel free to fork and customize for your own use!

## 📄 License

MIT License - feel free to use this template for your own portfolio.

---

**Need help?** Open an issue or check the TODO comments in the HTML file for specific customization guidance.