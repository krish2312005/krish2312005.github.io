# Krish Patel - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This website showcases professional experience, projects, and skills in an elegant and interactive design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **About**: Personal information and statistics
3. **Experience**: Professional timeline with work history
4. **Projects**: Featured projects with technologies used
5. **Skills**: Technical skills organized by category
6. **Contact**: Contact information and contact form

## Customization Guide

### Personal Information

Update the following in `index.html`:

```html
<!-- Update name and title -->
<title>Your Name - Portfolio</title>
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>

<!-- Update social links -->
<a href="https://github.com/yourusername" target="_blank" class="social-link">
<a href="https://linkedin.com/in/yourprofile" target="_blank" class="social-link">

<!-- Update contact information -->
<span>your.email@example.com</span>
<span>Your Location</span>
<span>Your Phone Number</span>
```

### Projects

Replace the project cards in the projects section with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-globe"></i> <!-- Change icon -->
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description here.</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" target="_blank" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

### Skills

Update the skills section with your technical skills:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-react"></i>
            <span>React</span>
        </div>
        <!-- Add more skills -->
    </div>
</div>
```

### Experience

Update the timeline with your work experience:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="period">2023 - Present</span>
        </div>
        <ul>
            <li>Your responsibility 1</li>
            <li>Your responsibility 2</li>
            <li>Your responsibility 3</li>
        </ul>
    </div>
</div>
```

### Colors and Styling

The main color scheme can be customized in `styles.css`:

```css
/* Primary colors */
--primary-color: #2563eb;
--secondary-color: #fbbf24;
--accent-color: #667eea;

/* Background colors */
--bg-primary: #ffffff;
--bg-secondary: #f8fafc;
--bg-dark: #1f2937;
```

## File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── New Resume - Professional.pdf  # Your resume
```

## Deployment

### Option 1: GitHub Pages (Free)

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site will be deployed instantly
4. You can set up a custom domain later

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Deploy automatically on every push

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

1. **Optimize Images**: Use WebP format and compress images
2. **Minify CSS/JS**: Use tools like UglifyJS and CSSNano
3. **Enable Gzip**: Compress files on your server
4. **Use CDN**: Load Font Awesome and Google Fonts from CDN

## SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML structure
- Open Graph tags (can be added)
- Structured data (can be added)

## Contact Form

The contact form currently shows a success message. To make it functional:

1. **EmailJS**: Use EmailJS service
2. **Formspree**: Use Formspree for form handling
3. **Backend**: Create a simple backend API

Example with EmailJS:

```javascript
// Add EmailJS script to HTML
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>

// Initialize EmailJS
emailjs.init("YOUR_USER_ID");

// Update form submission
emailjs.send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", {
    name: name,
    email: email,
    subject: subject,
    message: message
});
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing this portfolio, feel free to:
- Check the code comments for guidance
- Modify the CSS variables for easy color changes
- Add your own sections as needed

## Credits

- Fonts: [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts
- Icons: [Font Awesome](https://fontawesome.com/)
- Design inspiration from modern portfolio trends 