# Gokul Seshiah - Personal Website

A beautiful, modern personal website built with HTML, TailwindCSS, and vanilla JavaScript.

## Features

- 🎨 **Modern UI Design** - Clean, responsive design with TailwindCSS
- ⚡ **Interactive Elements** - Smooth animations and transitions
- 📱 **Mobile Responsive** - Works perfectly on all devices
- 🌙 **Smooth Scrolling** - Seamless navigation between sections
- ⌨️ **Typing Effect** - Dynamic text animation in hero section
- 📧 **Contact Form** - Functional contact form with validation
- 🎯 **Project Showcase** - Portfolio section with project cards
- 💼 **Skills Display** - Technical skills overview

## Sections

- **Home** - Hero section with animated typing effect
- **About** - Personal introduction and background
- **Projects** - Featured projects showcase
- **Skills** - Technical skills and expertise
- **Contact** - Contact form and information

## Technologies Used

- **HTML5** - Semantic markup
- **TailwindCSS** - Modern CSS framework
- **JavaScript (ES6+)** - Interactive functionality
- **Font Awesome** - Icon library
- **Google Fonts (Inter)** - Typography

## Getting Started

### Prerequisites

- A modern web browser
- Local web server (optional but recommended)

### Installation

1. Clone or download the project files
2. Open `index.html` in your web browser
3. Or serve with a local web server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using Live Server extension in VS Code
```

### Customization

#### Personal Information

Update the following in `index.html`:

- Name: Change "Gokul Seshiah" to your name
- Email: Update contact email addresses
- Social links: Add your actual social media URLs
- Content: Modify about section, projects, and skills

#### Styling

The design uses TailwindCSS via CDN. You can customize:

- Colors: Modify gradient classes and color schemes
- Fonts: Change the Google Font import
- Layout: Adjust Tailwind utility classes
- Animations: Modify CSS animations in the `<style>` section

#### Projects

Update the projects section with your actual projects:

1. Change project titles and descriptions
2. Update technology tags
3. Add real project links
4. Replace placeholder icons if needed

## File Structure

```
personal-website/
├── index.html          # Main HTML file
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/             # Images and other assets (if needed)
```

## Features Explained

### Typing Animation
The hero section features a typing effect that cycles through different roles. You can customize the `typingTexts` array in `script.js`.

### Smooth Scrolling
Navigation links use smooth scrolling to sections. The header is fixed and becomes more prominent on scroll.

### Contact Form
The contact form includes:
- Client-side validation
- Email format checking
- Success/error message display
- Form reset after submission

### Responsive Design
The website is fully responsive with:
- Mobile-first approach
- Collapsible navigation menu
- Flexible grid layouts
- Optimized typography

## Deployment

### Static Hosting
Deploy to any static hosting service:

- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Enable in repository settings
- **Firebase Hosting**: Use Firebase CLI

### Custom Domain
Update the domain in your hosting provider's settings and ensure all links work correctly.

## Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

The website is optimized for:
- Fast loading with CDN resources
- Minimal JavaScript
- Optimized images (when added)
- Efficient CSS with Tailwind

## Contributing

Feel free to fork this project and customize it for your own use!

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ by Gokul Seshiah**
