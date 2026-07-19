# Single Page CV

A clean, professional single-page CV/Resume built with HTML and CSS. Designed to fit perfectly on a single page while remaining responsive and print-ready.

## 🔗 Project URL

Project URL: https://sudhanshusingh-g.github.io/cv/

## 🌟 Features

- **Single Page Design** - Fits perfectly on one letter-sized page (8.5" × 11")
- **Print Ready** - Optimized for printing with proper page breaks and spacing
- **Responsive** - Works on desktop, tablet, and mobile devices
- **No Scroll** - All content visible without scrolling
- **Scalable** - Automatically adapts if you add more sections (like Projects)
- **Professional Design** - Green and blue accent colors with clean typography
- **SEO Optimized** - Includes proper meta tags and semantic HTML
- **Accessibility** - Properly structured HTML with semantic elements

## 🚀 Quick Start

### Prerequisites

No dependencies required! This is a pure HTML and CSS project.

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime, etc.) for customization
- Git (optional, for version control)

### Running the Project

#### Option 1: Open in Browser (Easiest)

```bash
# Simply double-click the index.html file
# Or right-click → Open with → Browser
```

#### Option 2: Live Server (VS Code)

```bash
# Install the "Live Server" extension in VS Code
# Right-click on index.html → Open with Live Server
# The CV will open at http://127.0.0.1:5500
```

#### Option 3: Python HTTP Server

```bash
# Navigate to the project directory
cd path/to/single-page-cv

# Python 3.x
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

## 📋 Customization

Edit the `index.html` file to add your personal information:

### Update Header Information

```html
<header>
  <h1>Your Name</h1>
  <p>Your Title</p>
  <address>
    <p>Your City, State</p>
    <p>Email: your.email@example.com</p>
    <p>Phone: +[your-number]</p>
  </address>
</header>
```

### Add/Edit Sections

- **Skills** - Update the skills list
- **Education** - Add your educational background
- **Experience** - Add your work experience
- **Projects** - Add a new section for projects (will auto-fit to 1 page)

### Modify Colors

Edit the CSS variables in the `<style>` tag:

```css
:root {
  --primary-green: #2ecc71;    /* Section headings */
  --link-blue: #3498db;         /* Links and company names */
  --text-dark: #333;            /* Main text */
  --text-light: #666;           /* Secondary text */
}
```

## 🖨️ Printing

### From Browser

1. **Print to PDF:**

   - Press `Ctrl+P` (or `Cmd+P` on Mac)
   - Select "Save as PDF"
   - Ensure "Background graphics" is enabled
   - Click "Save"
2. **Print to Paper:**

   - Press `Ctrl+P` (or `Cmd+P` on Mac)
   - Select your printer
   - Ensure margins are set to "Minimal" or "None"
   - Click "Print"

### Print Settings

- **Paper Size:** Letter (8.5" × 11")
- **Margins:** 0.5 inch
- **Orientation:** Portrait
- **Background Graphics:** Enabled (to show colors)

## 📁 File Structure

```
single-page-cv/
├── index.html          # Main CV file (HTML + CSS)
├── README.md           # This documentation
└── favicon.ico         # Browser tab icon (optional)
```

## 🌐 Browser Support

- ✅ Chrome/Chromium 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

## 📐 Page Layout

The CV uses a single-page design with automatic spacing adjustment:

- **Header** - Name, title, and contact info
- **Skills** - List of technical skills
- **Education** - Educational background
- **Experience** - Work experience entries
- **Across the Internet** - Links section (GitHub, LinkedIn, etc.)
- **Footer** - Copyright info

## 💡 Tips for Keeping It to 1 Page

1. **Font Sizes** - Current sizes are optimized for single page
2. **Spacing** - CSS uses minimal margins that scale with content
3. **Content Length** - Keep bullet points concise (1-2 lines each)
4. **Sections** - Limit to 3-4 main sections for best results
5. **Experience Entries** - Keep to 2-3 entries maximum

## ✏️ Adding New Sections

To add a new section (like Projects):

```html
<section>
  <h2>Projects</h2>
  
  <article>
    <h3>Project Name</h3>
    <p><strong>Technologies:</strong> HTML, CSS, JavaScript</p>
  
    <ul>
      <li>Project achievement or feature</li>
      <li>Another achievement</li>
    </ul>
  </article>
</section>
```

The CSS automatically handles spacing to keep everything on 1 page.

## 🎨 Styling Guide

The CSS includes:

- **Responsive typography** - Font sizes adjust for print
- **Print media queries** - Optimized for paper output
- **Flexible spacing** - Uses inches for consistency with print
- **Color scheme** - Professional green and blue accents

## 🤝 Contributing

Feel free to customize and modify this template for your own use!

## 📝 License

Free to use and modify for personal purposes.

## ❓ Troubleshooting

### Content overlaps on print

- Check browser zoom is at 100%
- Ensure "Background graphics" is enabled in print settings
- Reduce content length

### Extra blank page appears

- Go to print settings and disable "Background graphics"
- Ensure margins are minimal

### Colors don't show on print

- Enable "Background graphics" in browser print settings
- Try printing to PDF first to test

### Mobile display issues

- Make sure viewport meta tag is present
- Test in multiple browsers
- Adjust zoom level if needed
