# Adrian Buba - Artist Portfolio Website

A minimalist, static website for contemporary artist Adrian Buba, designed for hosting on GitHub Pages.

## Overview

This website showcases the work of Adrian Buba, a Romanian-French contemporary artist known for exploring the boundary between abstraction and figuration. The design emphasizes clean lines, generous white space, and a gallery-like aesthetic.

## Features

- **Responsive Design**: Fully responsive across all devices
- **Gallery with Lightbox**: Interactive masonry grid gallery with filtering
- **Smooth Animations**: Subtle transitions and micro-interactions
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Static Site**: No server required, perfect for GitHub Pages

## Structure

```
buba/
├── index.html          # Homepage with hero section
├── biography.html      # Artist biography and timeline
├── gallery.html        # Artwork gallery with filters
├── exhibitions.html    # Past and upcoming exhibitions
├── contact.html        # Contact form and information
├── 404.html           # Custom 404 error page
├── css/
│   └── styles.css     # Custom styles
├── js/
│   └── main.js        # JavaScript functionality
└── assets/
    └── images/        # Local images (to be added)
```

## Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Custom CSS**: Additional styling in `css/styles.css`
- **Vanilla JavaScript**: No dependencies
- **Google Fonts**: Playfair Display & Inter

## Setup for GitHub Pages

1. Push this repository to GitHub
2. Go to Settings → Pages
3. Set source to "Deploy from a branch"
4. Select main branch and root folder
5. Save and wait for deployment

Your site will be available at: `https://[username].github.io/buba/`

## Customization

### Replacing Images

Currently, images are loaded from external URLs. To use local images:

1. Add your images to `assets/images/`
2. Update image sources in HTML files from external URLs to local paths:
   ```html
   <!-- Change from: -->
   <img src="https://external-url.com/image.jpg" alt="...">

   <!-- To: -->
   <img src="assets/images/image.jpg" alt="...">
   ```

### Updating Content

- Edit HTML files directly to update text content
- Modify `css/styles.css` for custom styling
- Update `js/main.js` for functionality changes

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Optimizations

- Lazy loading for images (when using data-src attributes)
- Minimal JavaScript
- Optimized CSS delivery
- Clean, semantic HTML

## Contact Form

The contact form is styled but requires backend integration for actual email functionality. Options:

1. Use a service like Formspree or Netlify Forms
2. Implement with serverless functions
3. Use a third-party form service

## License

All artwork © Adrian Buba. Website code can be modified for personal use.

## Credits

Designed and developed with attention to gallery aesthetics and artist presentation standards.