# Ethio Coffee Co.

Premium Ethiopian Coffee Roasters - Toronto's premier source for single-origin Ethiopian coffee.

## Overview

A stylish, elegant portfolio website showcasing our Ethiopian coffee roasting business. We specialize in supplying coffee shops and micro cafes across the Greater Toronto Area with exceptional single-origin Ethiopian beans.

## Pages

- **Home** (`index.html`) - Hero section, introduction, features, and call-to-action
- **About** (`about.html`) - Our story, mission, and values
- **Coffee** (`coffee.html`) - Our coffee selection and wholesale partnership information
- **Contact** (`contact.html`) - Contact form and business information

## Local Development

To run locally:

```bash
# Using npm (requires Node.js)
npm start

# Or using Python
python -m http.server 3000

# Or using PHP
php -S localhost:3000
```

Then open `http://localhost:3000` in your browser.

## Deployment to Vercel

### Option 1: Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Option 2: GitHub Integration

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

Vercel will automatically detect this as a static site and deploy it.

## Customization

### Updating Content

- Edit the HTML files directly to change text content
- Images are loaded from Unsplash - replace URLs with your own images
- Update contact information in `contact.html` and footer sections

### Styling

All styles are in `css/style.css`. Key customizations:

- **Colors**: Update CSS variables in `:root` selector
- **Fonts**: Change Google Fonts imports in HTML `<head>` and `--font-*` variables
- **Spacing**: Adjust padding/margin values in section classes

### Colors (CSS Variables)

```css
--color-primary: #2C1810;      /* Deep brown */
--color-secondary: #8B4513;    /* Coffee brown */
--color-accent: #C9A961;       /* Gold */
--color-cream: #FAF6F0;        /* Background cream */
```

## Tech Stack

- Pure HTML5, CSS3, JavaScript
- No frameworks or build tools required
- Google Fonts (Cormorant Garamond, Montserrat)
- Responsive design
- Optimized for Vercel deployment

## License

MIT License
