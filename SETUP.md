# Professional Resume Website

This folder contains a complete, professional resume website ready for deployment.

## 📁 File Structure

```
resume-website/
├── index.html          # Main HTML file with your resume content
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript for interactions and animations
├── package.json        # NPM configuration for deployment
├── README.md          # Comprehensive setup and customization guide
└── .gitignore         # Git ignore file for clean repositories
```

## 🚀 Quick Deploy Commands

### Local Testing
```bash
# Option 1: Using Python (if installed)
python -m http.server 8080

# Option 2: Using Node.js serve package
npx serve .

# Option 3: Using any local server of your choice
```

### Deploy to Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy (from project directory)
vercel

# Follow prompts to deploy
```

### Deploy to Netlify
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy

# For production deployment
netlify deploy --prod
```

## ✏️ First Steps to Customize

1. **Replace placeholder content** in `index.html`:
   - Your name and job title
   - Contact information
   - Work experience
   - Skills and technologies
   - Project descriptions

2. **Add your professional photo**:
   - Replace the placeholder image URL
   - Use a high-quality, professional headshot

3. **Update colors** in `styles.css` if desired:
   - Modify the CSS custom properties at the top

4. **Add your resume PDF**:
   - Place your resume file in this directory
   - Update the download link in the HTML

## 🌐 Live Preview

After starting the local server, visit: http://localhost:8080

## 📞 Support

Check the comprehensive README.md file for detailed customization instructions and deployment options.