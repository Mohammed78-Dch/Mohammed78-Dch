# Portfolio Website - Deployment Guide

This repository contains a professional portfolio website showcasing Mohammed Dechraoui's CV as Data Scientist, AI Engineer, and ML Engineer.

## 🚀 Quick Start

### Local Development
1. Clone this repository
2. Open `index.html` in your web browser, or
3. Run a local server:
   ```bash
   python3 -m http.server 8080
   ```
4. Visit `http://localhost:8080`

## 🌐 Deploy to GitHub Pages

To make your portfolio live on the internet:

### Option 1: Deploy from main branch
1. Go to your repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Select `main` branch and `/ (root)` folder
5. Click Save
6. Your site will be live at: `https://mohammed78-dch.github.io/Mohammed78-Dch/`

### Option 2: Custom domain (optional)
1. Buy a domain (e.g., from Namecheap, Google Domains)
2. Add a `CNAME` file with your domain name
3. Configure DNS settings with your domain provider
4. Update GitHub Pages settings to use custom domain

## 📁 File Structure

```
.
├── index.html       # Main HTML file with all content
├── style.css        # All styling and responsive design
├── script.js        # Interactive features and animations
├── README.md        # Original CV in markdown format
└── PORTFOLIO.md     # This deployment guide
```

## ✨ Features

- **Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Modern UI**: Purple/blue gradient theme with smooth animations
- **Fast Loading**: Minimal dependencies, optimized performance
- **SEO Ready**: Semantic HTML and meta tags
- **Accessible**: WCAG compliant with skip links

## 🎨 Customization

### Update Personal Information
Edit `index.html` and update:
- Contact links (LinkedIn, GitHub)
- Project details
- Skills and expertise
- Education and certifications

### Change Colors
Edit `style.css` variables in the `:root` section:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... */
}
```

### Add New Sections
1. Add HTML in `index.html`
2. Add corresponding CSS in `style.css`
3. Update navigation links if needed

## 🔧 Dependencies

The portfolio uses only one external dependency:
- **Font Awesome 6.4.0** (CDN) - For icons

All other code is custom-written with no frameworks required.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This is a personal portfolio website. Feel free to use it as inspiration, but please don't copy it directly. Create your own unique version!

## 🤝 Contributing

This is a personal portfolio, but if you find bugs or have suggestions:
1. Open an issue
2. Submit a pull request
3. Contact via LinkedIn or GitHub

## 📞 Contact

- **LinkedIn**: [mohammed-dechraoui](https://www.linkedin.com/in/mohammed-dechraoui)
- **GitHub**: [Mohammed78-Dch](https://github.com/Mohammed78-Dch)
- **Location**: Rabat, Morocco

---

**Built with ❤️ by Mohammed Dechraoui**
*Last Updated: December 2024*
