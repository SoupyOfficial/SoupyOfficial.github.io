# Personal Portfolio Website

A clean, modern, and responsive personal portfolio website for software engineers. This template includes three main sections: About/Contact, Projects, and Resume/Links, with a professional design optimized for GitHub Pages deployment.

## 🌟 Features

- **Responsive Design**: Looks great on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean design with smooth animations and hover effects
- **Three Main Sections**:
  - About/Contact with downloadable vCard
  - Projects showcase (3-5 projects with links and screenshots)
  - Resume/Links section with social media integration
- **Performance Optimized**: Fast loading with lazy loading images
- **Accessibility**: Screen reader friendly with proper ARIA labels
- **SEO Ready**: Proper meta tags and semantic HTML structure
- **Easy to Customize**: Simple HTML/CSS/JS structure for easy modifications

## 🚀 Quick Start

### Option 1: GitHub Pages Deployment
1. Fork this repository
2. Rename it to `yourusername.github.io`
3. Customize the content (see customization guide below)
4. Enable GitHub Pages in repository settings
5. Your site will be available at `https://yourusername.github.io`

### Option 2: Vercel Deployment
1. Fork this repository
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy with default settings
4. Customize the content

### Option 3: Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   ```
2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```
3. Visit `http://localhost:8000` in your browser

## 📝 Customization Guide

### Personal Information
Edit the following in `index.html`:

1. **Basic Info** (Lines 6-7):
   ```html
   <meta name="description" content="Software Engineer Portfolio - Your Name">
   <title>Your Name - Software Engineer</title>
   ```

2. **Navigation and Hero Section** (Lines 15, 35-38):
   ```html
   <!-- Update navigation logo -->
   <a href="#home">Your Name</a>
   
   <!-- Update hero section -->
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   <h2 class="hero-subtitle">Your Title</h2>
   <p class="hero-description">Your description here...</p>
   ```

3. **About Section** (Lines 55-85):
   - Update your biography
   - Modify technical skills in the skill tags
   - Add or remove skills as needed

4. **Contact Information** (Lines 270-330):
   - Update email addresses
   - Update phone number
   - Update location
   - Update social media links

### Projects Section
Located in `index.html` (Lines 90-230):

1. **Replace Project Content**:
   ```html
   <div class="project-card">
     <div class="project-image">
       <img src="images/your-project.svg" alt="Your Project" loading="lazy">
     </div>
     <div class="project-content">
       <h3 class="project-title">Your Project Title</h3>
       <p class="project-description">Your project description...</p>
       <div class="project-tech">
         <span class="tech-tag">Technology 1</span>
         <span class="tech-tag">Technology 2</span>
       </div>
       <div class="project-links">
         <a href="https://github.com/yourusername/project" target="_blank" class="project-link">
           <i class="fab fa-github"></i> Code
         </a>
         <a href="https://yourproject.com" target="_blank" class="project-link">
           <i class="fas fa-external-link-alt"></i> Live Demo
         </a>
       </div>
     </div>
   </div>
   ```

2. **Add Project Images**:
   - Replace SVG files in `/images/` directory
   - Or use JPG/PNG images (update file extensions in HTML)
   - Recommended size: 400x200px

### Social Media & Resume Links
Located in `index.html` (Lines 250-290):

1. **Update Social Links**:
   ```html
   <a href="https://github.com/yourusername" target="_blank" class="social-link">
   <a href="https://linkedin.com/in/yourusername" target="_blank" class="social-link">
   <a href="mailto:your.email@example.com" class="social-link">
   <a href="https://twitter.com/yourusername" target="_blank" class="social-link">
   ```

2. **Replace Resume PDF**:
   - Replace `resume.pdf` with your actual resume
   - Keep the same filename or update the link in HTML

### vCard Contact File
Edit `contact.vcf`:
```
BEGIN:VCARD
VERSION:3.0
FN:Your Full Name
N:LastName;FirstName;;;
TITLE:Your Job Title
ORG:Your Company
EMAIL;TYPE=INTERNET:your.email@example.com
TEL;TYPE=CELL:+1234567890
ADR;TYPE=HOME:;;Your Address;City;State;ZIP;Country
URL:https://yourwebsite.com
NOTE:Your professional note here
END:VCARD
```

### Colors and Styling
Primary colors are defined in `style.css`:

1. **Change Color Scheme** (Lines 80-85):
   ```css
   .btn-primary {
     background: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);
   }
   
   .highlight {
     background: linear-gradient(45deg, #your-color3 0%, #your-color4 100%);
   }
   ```

2. **Main Brand Colors**:
   - Primary: `#667eea` and `#764ba2`
   - Accent: `#2c3e50`
   - Update these throughout the CSS file

### Adding More Sections
To add new sections:

1. **Add Navigation Link**:
   ```html
   <a href="#your-section" class="nav-link">Your Section</a>
   ```

2. **Add Section HTML**:
   ```html
   <section id="your-section" class="your-section">
     <div class="container">
       <h2 class="section-title">Your Section Title</h2>
       <!-- Your content here -->
     </div>
   </section>
   ```

3. **Add Section Styles** in `style.css`:
   ```css
   .your-section {
     padding: 100px 0;
     background: white; /* or your preferred background */
   }
   ```

## 🛠 Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **Vanilla JavaScript**: No framework dependencies
- **Font Awesome**: Icons
- **SVG**: Vector graphics for project images

## 📱 Browser Support

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Android Chrome)

## 📄 File Structure

```
├── index.html          # Main HTML file
├── style.css          # Styles and responsive design
├── script.js          # Interactive functionality
├── contact.vcf        # Downloadable contact card
├── resume.pdf         # Resume PDF (replace with yours)
├── images/            # Project screenshots/images
│   ├── project1.svg
│   ├── project2.svg
│   ├── project3.svg
│   └── project4.svg
└── README.md          # This file
```

## 🎨 Customization Tips

1. **Images**: Use high-quality images (400x200px for projects)
2. **Content**: Keep descriptions concise and impactful
3. **Colors**: Maintain consistency throughout the design
4. **Performance**: Optimize images for web (use WebP if possible)
5. **Mobile**: Test on various screen sizes
6. **SEO**: Update meta descriptions and titles

## 🚀 Deployment Options

### GitHub Pages
- Free hosting for static websites
- Custom domain support
- SSL/HTTPS included
- Automatic deployment from repository

### Vercel
- Fast global CDN
- Automatic deployments
- Custom domains
- Analytics included

### Netlify
- Drag-and-drop deployment
- Form handling
- Custom domains
- SSL certificates

## 📧 Support

If you need help customizing this template:

1. Check the customization guide above
2. Review the HTML/CSS comments
3. Open an issue in the repository
4. Contact: [your.email@example.com]

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Credits

- Design inspiration from modern portfolio websites
- Icons by [Font Awesome](https://fontawesome.com)
- Fonts from Google Fonts (system fonts used for performance)

---

**Happy coding! 🚀**

Feel free to customize this template to match your personal brand and showcase your unique projects and skills.