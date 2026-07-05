# Setup Guide - Tharindu Dilshan Portfolio

## Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code recommended)
- Git

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/DBT-DILSHAN/DBT-DILSHAN.github.io.git
cd DBT-DILSHAN.github.io
```

2. **Local Development**
```bash
# Using Python 3
python -m http.server 8000

# Or using Node.js
npx http-server
```
Then open `http://localhost:8000` in your browser.

## 📁 Project Structure

```
DBT-DILSHAN.github.io/
├── index.html              # Main portfolio page
├── manifest.json           # PWA configuration
├── robots.txt             # SEO robots configuration
├── sitemap.xml            # XML sitemap for search engines
├── cv.pdf                 # Your resume
├── README.md              # Project documentation
├── .gitignore             # Git ignore rules
├── SETUP.md               # This file
└── assets/
    ├── icons/             # Favicon & app icons
    │   ├── favicon.png    # 192x192px
    │   └── apple-touch-icon.png  # 180x180px
    └── images/            # Portfolio images
        └── og-cover.jpg   # Open Graph image (1280x720px)
```

## 🎯 Customization

### 1. Update Personal Information
Edit `index.html` and update:
- Meta tags (name, description, keywords)
- Profile information
- Contact details
- Social media links

### 2. Add Your Images
Place your images in:
- **Icons**: `assets/icons/` (favicon.png, apple-touch-icon.png)
- **Images**: `assets/images/` (og-cover.jpg and other portfolio images)

### 3. Update CV
Replace `cv.pdf` with your latest resume.

### 4. Customize Colors
Edit CSS variables in `index.html` `<style>` section:
```css
:root {
  --gold: #10B981;           /* Primary color */
  --gold-light: #34D399;     /* Light variant */
  --gold-dark: #059669;      /* Dark variant */
  /* ... more variables ... */
}
```

### 5. Modify Content
Update your portfolio sections directly in the HTML file.

## 🚀 Deployment

### GitHub Pages (Automatic)
The site automatically deploys to GitHub Pages when you push to the `main` branch.

### Vercel Deployment
1. Connect your GitHub repository to Vercel
2. Vercel automatically deploys on every push
3. View your site at: https://dbt-dilshan-github-io.vercel.app

## 🔍 SEO Optimization

- ✅ Meta tags configured
- ✅ Sitemap included
- ✅ robots.txt configured
- ✅ Open Graph tags for social sharing
- ✅ Canonical URL set

## 📱 Testing

### Responsive Design
Test at different breakpoints:
- Mobile: 320px - 480px
- Tablet: 481px - 768px
- Desktop: 769px+

### Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Performance
- Check with Google PageSpeed Insights
- Monitor Core Web Vitals
- Test with Chrome DevTools

## 🎨 Theme Switching

Users can toggle between dark and light themes using the theme switch button in the navbar. Your preferences are saved in browser storage.

## 🐛 Troubleshooting

### Images not loading
- Check file paths in `index.html`
- Verify images exist in `assets/` folders
- Use relative paths (e.g., `assets/images/og-cover.jpg`)

### Styles not applying
- Clear browser cache (Ctrl+Shift+Del or Cmd+Shift+Del)
- Check CSS variable names
- Verify no conflicting styles

### Theme not changing
- Check browser console for JavaScript errors
- Verify localStorage is enabled
- Try different browser

## 📝 License

This portfolio is personal intellectual property.

## 📞 Support

For issues or questions, contact: dilshantharindu212@gmail.com

---

*Last Updated: July 2026*
