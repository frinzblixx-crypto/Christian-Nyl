# Professional Biography Website with Gallery

A modern, responsive professional biography website featuring a portfolio gallery with filtering capabilities.

## Features

✨ **Key Features:**
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Professional Navigation** - Smooth scrolling navigation menu
- **Hero Section** - Eye-catching introduction banner
- **About Section** - Professional biography and skills showcase
- **Portfolio Gallery** - Filterable project gallery with hover effects
- **Experience Timeline** - Visual timeline of professional experience
- **Contact Form** - Functional contact form for inquiries
- **Modern UI** - Clean, professional design with smooth animations
- **Accessibility** - Semantic HTML and proper contrast ratios

## File Structure

```
biot/
├── index.html       # Main HTML file
├── styles.css       # Stylesheet with responsive design
├── script.js        # JavaScript for interactivity
└── README.md        # This file
```

## Getting Started

### 1. Installation

No installation required! This is a static website that works in any modern web browser.

### 2. Opening the Website

Simply open `index.html` in your web browser:
- Double-click `index.html` on your computer, OR
- Right-click `index.html` → "Open with" → Choose your browser, OR
- Use a local server (recommended for development)

### 3. Using a Local Server (Optional but Recommended)

For development purposes, it's best to serve files through a local server:

**Using Python 3:**
```bash
python -m http.server 8000
```

**Using Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**
```bash
npx http-server
```

Then open your browser and navigate to `http://localhost:8000`

## Customization Guide

### 1. Personalize Content

Edit `index.html` to customize:
- **Name & Title**: Change "John Doe" in navigation and hero section
- **About Section**: Update biography text and skills list
- **Experience**: Modify timeline items with your actual experience
- **Contact Info**: Add your email or social media links

### 2. Replace Placeholder Images

The website uses placeholder images. Replace them with your own:

```html
<!-- Replace this in the About section -->
<img src="https://via.placeholder.com/300x300?text=Profile+Photo" alt="Profile Photo">

<!-- With your image -->
<img src="path/to/your/profile-photo.jpg" alt="Profile Photo">
```

For gallery items:
```html
<img src="https://via.placeholder.com/400x300?text=Project+1" alt="Project 1">
```

### 3. Customize Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2c3e50;      /* Main color */
    --secondary-color: #3498db;    /* Accent color */
    --accent-color: #e74c3c;       /* Highlight color */
    --light-bg: #ecf0f1;           /* Light background */
    --dark-text: #2c3e50;          /* Text color */
    --light-text: #ffffff;         /* Light text color */
}
```

### 4. Update Gallery Items

Add or remove gallery items in the `.gallery-grid` section:

```html
<div class="gallery-item" data-category="design">
    <img src="your-image.jpg" alt="Project Name">
    <div class="gallery-overlay">
        <h3>Your Project Name</h3>
        <p>Project Category</p>
    </div>
</div>
```

The `data-category` attribute connects to filter buttons: "design", "development", or "photography".

### 5. Add More Sections

You can extend the website by:
1. Adding new `<section>` elements in `index.html`
2. Adding corresponding styles in `styles.css`
3. Adding functionality in `script.js` if needed
4. Update navigation links in the navbar

## Features Explanation

### Gallery Filtering
Click the filter buttons to show/hide projects by category:
- **All** - Display all projects
- **Design** - Show design projects only
- **Development** - Show development projects only
- **Photography** - Show photography projects only

### Smooth Scrolling
Click any navigation link to smoothly scroll to that section.

### Contact Form
The contact form includes:
- Name field
- Email field
- Message textarea
- Form validation
- Success message on submission

### Animations
- Fade-in animations on page load
- Hover effects on gallery items
- Smooth transitions throughout
- Scroll-triggered animations for elements

## Browser Compatibility

This website works on:
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Android)

## Tips for Best Results

1. **Use High-Quality Images**: Gallery images look best at 400x300px or larger
2. **Keep Text Concise**: Mobile users appreciate shorter paragraphs
3. **Test Responsiveness**: Open in browser developer tools (F12) and test mobile view
4. **Update Regularly**: Keep content fresh and up-to-date
5. **Optimize Images**: Compress images to improve page load speed

## SEO Tips

Improve search engine visibility:
1. Update the page title in `<head>`: `<title>Your Name - Professional Portfolio</title>`
2. Add meta description: `<meta name="description" content="Your description here">`
3. Use descriptive alt text for images
4. Keep URLs clean and meaningful

## Deployment

To publish your website:

1. **GitHub Pages** (Free)
   - Push files to GitHub repository
   - Enable GitHub Pages in repository settings
   - Access at `username.github.io/repository-name`

2. **Netlify** (Free)
   - Drag and drop folder to Netlify
   - Get instant live URL

3. **Web Hosting** (Paid)
   - Upload files via FTP to your web hosting provider
   - Access via your domain name

## Support & Enhancements

Potential future enhancements:
- Blog section
- Testimonials section
- Service offerings
- Pricing table
- Dark mode toggle
- Language selector
- Integration with CMS

## License

This template is free to use and modify for your personal or professional use.

---

**Last Updated:** October 2025

For questions or customization help, refer to the inline comments in the code files.
