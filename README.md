# My Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript, designed to be deployed on GitHub Pages.

## 🌟 Features

- **Responsive Design**: Works perfectly on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, form validation, and hover effects
- **Performance Optimized**: Fast loading with optimized assets
- **Accessibility**: Built with accessibility best practices
- **Cross-browser Compatible**: Works on all modern browsers

## 🚀 Quick Start

1. **Clone this repository**
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>
   ```

2. **Open the website locally**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     ```

3. **Customize the content**
   - Edit `index.html` to update your personal information
   - Modify `styles.css` to change colors and styling
   - Update `script.js` to add custom functionality

## 📁 File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization

### Personal Information
Update the following sections in `index.html`:
- Hero section title and subtitle
- About section content
- Skills list
- Project descriptions
- Contact information

### Styling
Modify `styles.css` to:
- Change color scheme (search for `#6366f1` and other color values)
- Adjust fonts and typography
- Modify spacing and layout
- Update animations and transitions

### Functionality
Edit `script.js` to:
- Add new interactive features
- Modify form handling
- Customize animations
- Add new JavaScript functionality

## 🌐 Deploy to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon and select "New repository"
3. Name your repository: `<yourusername>.github.io`
4. Make it public
5. Don't initialize with README (we already have one)
6. Click "Create repository"

### Step 2: Upload Your Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop all your website files (`index.html`, `styles.css`, `script.js`)
3. Add a commit message like "Initial website upload"
4. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to your repository's "Settings" tab
2. Scroll down to "GitHub Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

### Step 4: Access Your Website
- Wait a few minutes for deployment
- Your website will be available at: `https://<yourusername>.github.io`
- Share this URL in your portfolio or resume!

## 🔄 Updating Your Website

To update your website:
1. Make changes to your local files
2. Commit and push to GitHub:
   ```bash
   git add .
   git commit -m "Update website content"
   git push origin main
   ```
3. GitHub Pages will automatically redeploy your site

## 🛠️ Local Development

### Using Live Server (VS Code Extension)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Your website will open in the browser with auto-reload

### Using Python
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

### Using Node.js
```bash
# Install serve globally
npm install -g serve

# Serve the current directory
serve .
```

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🎯 Performance Tips

- Images are optimized and use modern formats
- CSS and JavaScript are minified for production
- Fonts are loaded efficiently from Google Fonts
- Smooth animations use CSS transforms for better performance

## 🐛 Troubleshooting

### Website not showing up?
- Check that GitHub Pages is enabled in repository settings
- Ensure your repository is public
- Wait a few minutes for initial deployment

### Styling issues?
- Clear your browser cache
- Check browser console for CSS errors
- Verify all files are uploaded to GitHub

### Form not working?
- The contact form is for demonstration only
- To make it functional, you'll need a backend service
- Consider using services like Formspree or Netlify Forms

## 📚 Resources

- [GitHub Pages Documentation](https://pages.github.com/)
- [HTML5 Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).


Your portfolio website is now ready to showcase your skills and projects to the world!
