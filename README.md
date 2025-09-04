# Personal portfolio - Mrunal Kanta Muduli

![GitHub repo size](https://img.shields.io/github/repo-size/mrunaldev/mrunaldev.github.io)
![GitHub stars](https://img.shields.io/github/stars/mrunaldev/mrunaldev.github.io?style=social)
![GitHub forks](https://img.shields.io/github/forks/mrunaldev/mrunaldev.github.io?style=social)
[![X Follow](https://img.shields.io/twitter/follow/mrunalkanta4u?style=social)](https://twitter.com/intent/follow?screen_name=mrunalkanta4u)

This is my personal portfolio website, responsive for all devices, built using HTML, CSS, and JavaScript.

# Personal Portfolio - Mrunal Kanta Muduli

A responsive personal portfolio website showcasing professional experience, skills, and achievements. Built with modern web technologies and deployed on GitHub Pages.

## 🚀 Live Demo

Visit the live website: [https://mrunaldev.github.io](https://mrunaldev.github.io)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Build and Run Locally](#build-and-run-locally)
- [Deployment](#deployment)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## 📖 Overview

This is a professional portfolio website for Mrunal Kanta Muduli, a Technical Specialist at Hewlett Packard Enterprise. The website features a clean, modern design that is fully responsive across all devices and showcases professional experience, skills, education, certifications, and projects.

## ✨ Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Interactive Navigation**: Smooth page transitions and navigation
- **Professional Sections**:
  - About Me with professional summary
  - Skills and expertise showcase
  - Work experience timeline
  - Education background
  - Certifications and achievements
  - Client testimonials with modal popups
  - Project portfolio with filtering
  - Contact form
- **Modern UI/UX**: Clean, professional design with smooth animations
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Cross-browser Compatible**: Works on all modern browsers

## 🛠️ Tech Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox and grid layouts
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation
- **GitHub Pages**: Static site hosting

## 📁 Project Structure

```
mrunaldev.github.io/
├── assets/
│   ├── css/           # Stylesheets
│   ├── images/        # Images and icons
│   └── js/
│       └── script.js  # JavaScript functionality
├── website-demo-image/
│   ├── desktop.png    # Desktop demo screenshot
│   └── mobile.png     # Mobile demo screenshot
├── index.html         # Main HTML file
├── index.txt          # Text version (if needed)
├── LICENSE            # License file
├── LICENSE-MIT        # MIT License
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites

No special prerequisites are required as this is a static HTML website. You only need:
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor or IDE (VS Code, Sublime Text, etc.) for editing
- Git (for cloning the repository)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mrunaldev/mrunaldev.github.io.git
   cd mrunaldev.github.io
   ```

2. **Open the project**:
   - Open the project folder in your preferred text editor
   - Or navigate to the folder in your file explorer

## 🔧 Build and Run Locally

### Method 1: Direct File Opening
1. Navigate to the project directory
2. Double-click on `index.html` to open it in your default browser
3. The website will load and be fully functional

### Method 2: Local Development Server (Recommended)

For a better development experience, especially when making changes:

#### Using Python (if installed):
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Using Node.js (if installed):
```bash
# Install a simple HTTP server globally
npm install -g http-server

# Run the server
http-server
```

#### Using PHP (if installed):
```bash
php -S localhost:8000
```

#### Using Live Server (VS Code Extension):
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

After starting a local server, open your browser and navigate to:
- `http://localhost:8000` (or the port shown in your terminal)

## 📦 Deployment

### GitHub Pages (Automatic)

The project is configured for automatic deployment via GitHub Pages:

1. **Push changes** to the `main` branch
2. **GitHub Pages automatically builds and deploys** the site
3. **Access the live site** at `https://mrunaldev.github.io`

### Manual Deployment

To deploy on other platforms:

1. **Build the project** (no build step required for static files)
2. **Upload the files** to your hosting provider:
   - Upload all files and folders to the web root directory
   - Ensure `index.html` is in the root directory
   - Maintain the folder structure, especially the `assets/` directory

### Supported Hosting Platforms

- GitHub Pages ✅ (Current)
- Netlify
- Vercel
- Firebase Hosting
- AWS S3 + CloudFront
- Any static file hosting service

## 🎨 Customization

### Updating Personal Information

1. **Edit `index.html`**:
   - Update personal details in the contact section
   - Modify the about section content
   - Add/remove experience entries
   - Update skills and technologies

2. **Replace Images**:
   - Add your profile photo to `assets/images/`
   - Update client logos and testimonial images
   - Replace project screenshots

3. **Modify Styling**:
   - Edit CSS files in `assets/css/`
   - Customize colors, fonts, and layouts
   - Add new animations or effects

### Adding New Sections

1. **HTML Structure**: Add new sections in `index.html`
2. **CSS Styling**: Create corresponding styles in the CSS files
3. **JavaScript**: Add any interactive functionality in `assets/js/script.js`

### Key JavaScript Features

The `script.js` file includes:
- **Sidebar Toggle**: Mobile navigation functionality
- **Modal System**: Testimonial popup functionality
- **Portfolio Filter**: Project filtering by category
- **Form Validation**: Contact form validation
- **Page Navigation**: Smooth scrolling and page transitions

## 🤝 Contributing

Contributions are welcome! Here's how you can contribute:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/new-feature`
3. **Commit your changes**: `git commit -m 'Add some feature'`
4. **Push to the branch**: `git push origin feature/new-feature`
5. **Open a Pull Request**

### Contribution Guidelines

- Ensure your code follows the existing style
- Test your changes on multiple browsers and devices
- Update documentation if necessary
- Keep commits small and focused

## 🐛 Troubleshooting

### Common Issues

1. **Images not loading**:
   - Check file paths in HTML
   - Ensure images are in the correct `assets/images/` directory
   - Verify image file extensions match HTML references

2. **Styles not applying**:
   - Check CSS file paths in HTML
   - Clear browser cache
   - Ensure CSS files are in the correct `assets/css/` directory

3. **JavaScript not working**:
   - Check browser console for errors
   - Ensure `script.js` is properly linked in HTML
   - Verify JavaScript syntax

### Browser Compatibility

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

**Mrunal Kanta Muduli**
- Email: mrunalkanta4u@gmail.com
- Phone: +91 9663865026
- Location: Bengaluru, Karnataka, India
- Website: [https://mrunaldev.github.io](https://mrunaldev.github.io)

---

## 🙏 Acknowledgments

- Thanks to all the colleagues who provided testimonials
- Inspired by modern portfolio design trends
- Built with dedication and attention to detail

---

**Made with ❤️ by Mrunal Kanta Muduli**

## Contact

If you want to contact me you can reach me at [X](https://x.com/mrunalkanta4u).

## License

MIT
