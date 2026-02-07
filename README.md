# Mintlify - The Intelligent Documentation Platform

A responsive landing page for Mintlify, an intelligent knowledge platform designed to help teams create and maintain world-class documentation for both humans and AI.

## Overview

This project is a modern, visually appealing landing page showcasing Mintlify's features and value proposition. Built with clean HTML, CSS, and optimized for responsive design, it includes a sticky navigation bar, hero section, company testimonials, and feature showcase.

## Project Structure

```
Mintlify/
├── index.html          # Main HTML file with page structure
├── style.css           # Stylesheet with responsive design
├── README.md           # This file
└── Assets/
    ├── images/         # SVG and PNG images for the site
    │   ├── Mintlify_idjQU-FEBd_1.svg
    │   ├── hero-image-light.svg
    │   ├── bg-light.svg
    │   ├── features-1.png
    │   ├── features-2.png
    │   ├── features-3.png
    │   └── [other brand logos and assets]
    └── fonts/          # Custom font files
        └── Inter-VariableFont_slnt,wght.ttf
```

## Key Features

- **Sticky Navigation Bar** - Primary navigation remains accessible as users scroll
- **Hero Section** - Eye-catching introduction with email signup and product preview
- **Company Testimonials** - Trusted by leading companies
- **Feature Showcase** - Highlights AI-powered documentation capabilities
- **Responsive Design** - Optimized for all screen sizes
- **Modern Styling** - Clean design with custom color scheme using CSS variables

## Color Scheme

The project uses a carefully designed color palette:

- **Primary Color**: `#08090b` (Dark)
- **Secondary Color**: `#ffffff` (White)
- **Accent Color**: `#18e299` (Mountain Meadow Green)
- **Secondary Accent**: `#3f8a62` (Riptide)

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No external dependencies or build tools required

### How to Use

1. **Clone or download** the repository to your local machine
2. **Open** `index.html` in your web browser
3. **View** the landing page in action

For local development with a server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (with live-server)
npx live-server
```

Then navigate to `http://localhost:8000` in your browser.

## Customization

### Modifying Content

- Edit `index.html` to update text, links, and structure
- Update image paths in the `src` attributes to point to your own assets

### Styling Changes

- Modify variables in `:root` selector in `style.css` to change colors globally
- Edit specific selectors to adjust layout, spacing, and typography

### Adding Assets

- Place images in the `Assets/images/` folder
- Place fonts in the `Assets/fonts/` folder
- Update references in HTML and CSS accordingly

## Browser Compatibility

- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## License

This project is for educational and development purposes.

## Contact

For more information about Mintlify, visit [mintlify.com](https://www.mintlify.com)
