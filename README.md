# Professional Resume Website

A modern, responsive resume website built with HTML, CSS, and JavaScript. Perfect for showcasing your professional experience, skills, and projects to potential employers.

## ✨ Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **SEO Friendly**: Semantic HTML structure and meta tags
- **Easy Customization**: Well-organized code that's easy to modify
- **Performance Optimized**: Fast loading times and smooth animations

## 🚀 Quick Start

1. **Clone or download** this repository
2. **Customize the content** in `index.html` with your information
3. **Replace the placeholder image** with your professional photo
4. **Add your resume PDF** to the root directory
5. **Deploy** to your preferred hosting platform

## 📝 Customization Guide

### Personal Information

Edit the following sections in `index.html`:

```html
<!-- Update your name and title -->
<span class="name">Your Full Name</span>
<h2 class="hero-subtitle">Senior Software Engineer</h2>

<!-- Update contact information -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="tel:+1234567890">+1 (234) 567-890</a>
<span>Your City, State</span>

<!-- Update social media links -->
<a href="https://linkedin.com/in/yourprofile" target="_blank">
<a href="https://github.com/yourusername" target="_blank">
```

### Professional Photo

Replace the placeholder image:
1. Add your professional photo to the root directory
2. Update the image source in the hero section:

```html
<img src="your-photo.jpg" alt="Profile Picture" class="profile-img">
```

### Resume PDF

1. Add your resume PDF file to the root directory as `resume.pdf`
2. Or update the link in the hero section to match your filename:

```html
<a href="/your-resume.pdf" class="btn btn-secondary" target="_blank">
```

### Work Experience

Update the timeline section with your work history:

```html
<div class="timeline-content">
    <h3>Your Job Title</h3>
    <h4>Company Name</h4>
    <span class="date">Start Date - End Date</span>
    <ul>
        <li>Your accomplishment or responsibility</li>
        <li>Another achievement with metrics if possible</li>
    </ul>
</div>
```

### Skills

Modify the skills section to match your technical expertise:

```html
<div class="skill-items">
    <span class="skill-tag">Your Skill</span>
    <span class="skill-tag">Another Skill</span>
</div>
```

### Projects

Update the projects grid with your work:

```html
<div class="project-content">
    <h3>Project Name</h3>
    <p>Project description highlighting the problem solved and technologies used.</p>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
    <div class="project-links">
        <a href="https://your-project-demo.com" class="project-link" target="_blank">
            <i class="fas fa-external-link-alt"></i> Live Demo
        </a>
        <a href="https://github.com/yourusername/project" class="project-link" target="_blank">
            <i class="fab fa-github"></i> Code
        </a>
    </div>
</div>
```

## 🎨 Color Customization

Modify the CSS custom properties in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #1e40af;    /* Darker shade */
    --accent-color: #3b82f6;       /* Lighter shade */
    --text-primary: #1f2937;       /* Main text color */
    --text-secondary: #6b7280;     /* Secondary text color */
}
```

## 🌐 Deployment Options

### GitHub Pages (Free)

1. **Create a GitHub repository** for your resume website
2. **Upload all files** to the repository
3. **Go to Settings** → **Pages**
4. **Select source**: Deploy from a branch → main
5. **Your site will be available** at: `https://yourusername.github.io/repository-name`

### Netlify (Free)

1. **Create account** at [netlify.com](https://netlify.com)
2. **Drag and drop** your project folder to Netlify dashboard
3. **Your site will be deployed** automatically with a custom URL
4. **Optional**: Connect to GitHub for automatic deployments

### Vercel (Free)

1. **Create account** at [vercel.com](https://vercel.com)
2. **Import your project** from GitHub or upload files
3. **Deploy with one click**
4. **Get automatic HTTPS** and global CDN

### Traditional Web Hosting

Upload all files to your web hosting provider's public directory (usually `public_html` or `www`).

## 📱 Mobile Optimization

The website is fully responsive and includes:

- Mobile-first design approach
- Hamburger navigation menu for mobile devices
- Touch-friendly buttons and links
- Optimized images and fonts for all screen sizes
- Fast loading on mobile networks

## 🔧 Technical Details

### Technologies Used

- **HTML5**: Semantic markup for better SEO
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive features and animations
- **Font Awesome**: Icons for social media and UI elements
- **Google Fonts**: Professional typography (Inter font family)

### Performance Features

- **Optimized images**: Placeholder images with proper dimensions
- **Minified code**: Clean, efficient code structure
- **Progressive enhancement**: Works without JavaScript
- **Accessibility**: ARIA labels and semantic HTML
- **SEO optimized**: Meta tags and structured data

### Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📧 Contact Form Setup

The contact form includes client-side validation. To make it functional:

### Option 1: Email Service (Recommended)

Use a service like [Formspree](https://formspree.io/) or [Netlify Forms](https://www.netlify.com/products/forms/):

```html
<!-- For Formspree -->
<form action="https://formspree.io/f/your-form-id" method="POST">

<!-- For Netlify Forms -->
<form netlify>
```

### Option 2: Custom Backend

If you have backend development skills, you can:
1. Set up a server endpoint to handle form submissions
2. Update the JavaScript in `script.js` to send data to your endpoint
3. Implement email sending functionality

## 🎯 Best Practices

### Content Tips

1. **Keep it concise**: Use bullet points and quantify achievements
2. **Use action words**: Started with strong verbs (Led, Implemented, Designed)
3. **Include metrics**: Numbers and percentages make impact clear
4. **Tailor content**: Customize for the roles you're applying for
5. **Proofread**: Check for typos and grammatical errors

### Design Tips

1. **Professional photo**: Use a high-quality, professional headshot
2. **Consistent branding**: Keep colors and fonts consistent
3. **White space**: Don't overcrowd sections
4. **Visual hierarchy**: Use headings and spacing effectively
5. **Mobile first**: Always test on mobile devices

## 🔄 Updates and Maintenance

### Regular Updates

- Keep your experience and skills current
- Add new projects and achievements
- Update your resume PDF regularly
- Refresh your professional photo periodically

### Performance Monitoring

- Test loading speed with tools like Google PageSpeed Insights
- Check mobile responsiveness regularly
- Monitor for broken links
- Update dependencies and libraries as needed

## 📞 Support

If you need help customizing this template:

1. **Check the documentation** above for common customizations
2. **Review the code comments** in the HTML, CSS, and JavaScript files
3. **Test changes locally** before deploying
4. **Use browser developer tools** to debug styling issues

## 📄 License

This resume template is free to use for personal and commercial purposes. No attribution required, but appreciated!

---

**Good luck with your job search! 🎉**

Remember to customize all placeholder content with your actual information before deploying.