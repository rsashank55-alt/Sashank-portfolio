# Sashank Reddy M - Portfolio Website

A modern, animated portfolio website showcasing my interests, hobbies, and academic pursuits.

🌐 **Live Website:** [View Portfolio](https://rsashank55-alt.github.io/Sashank-portfolio/)

## Features

- ✨ Smooth animations and transitions
- 📱 Fully responsive design
- 🎨 Modern gradient design
- ⚡ Fast and lightweight
- 🎯 Interactive elements
- 🚀 GitHub Pages compatible

## Setup Instructions

1. **Add Your Photo:**
   - Place your profile photo in the same folder as `index.html`
   - Name it `photo.jpg` (or update the filename in `index.html` line 46)
   - Supported formats: JPG, PNG, WebP
   - Recommended size: 500x500 pixels or larger (square format works best)

2. **Add Your Achievement Photo:**
   - Place your football achievement photo in the same folder
   - Name it `trophy.jpg` (or update the filename in `index.html` line 82)
   - Supported formats: JPG, PNG, WebP
   - Recommended size: 1200x900 pixels or larger (landscape works great)

3. **Open the Website:**
   - Simply open `index.html` in your web browser
   - Or use a local server for better performance:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```
   - Then visit `http://localhost:8000` in your browser

## File Structure

```
Personal portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styling and animations
├── script.js       # Interactive JavaScript features
├── photo.jpg       # Your profile photo (add this)
├── trophy.jpg      # Football achievement photo (add this)
└── README.md       # This file
```

## Customization

You can easily customize:
- Colors: Edit the CSS variables in `styles.css` (lines 7-13)
- Content: Update the text in `index.html`
- Animations: Modify animation timings in `styles.css`

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Deployment

This portfolio is deployed on GitHub Pages. To deploy your own:

1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select the main branch as source
4. Your site will be live at `https://[username].github.io/[repository-name]`

Enjoy your portfolio website! 🚀

