# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Modern UI**: Clean and professional design with smooth animations
- **Project Showcase**: Filterable project gallery with hover effects
- **Contact Form**: Functional contact form with validation
- **Smooth Animations**: Scroll animations and transitions
- **Mobile Menu**: Hamburger menu for mobile devices

## Pages

1. **Home (index.html)**: Hero section, featured projects, skills showcase
2. **About (about.html)**: Personal information, skills, experience timeline
3. **Projects (projects.html)**: Full project portfolio with filtering
4. **Contact (contact.html)**: Contact form and location information

## File Structure

```
personal-portfolio/
│
├── index.html              # Home Page
├── about.html              # About Me
├── projects.html           # Projects Showcase
├── contact.html            # Contact Page
│
├── css/
│   ├── style.css           # Main styles
│   └── responsive.css      # Media queries
│
├── js/
│   └── script.js          # Interactivity (menu, animations)
│
├── assets/
│   ├── images/
│   │   ├── profile.jpg    # Your photo
│   │   ├── project1.png   # Project images
│   │   └── project2.png
│   │
│   ├── icons/
│   │   └── (social icons, UI icons)
│   │
│   └── resume/
│       └── resume.pdf       # Your CV
│
├── components/             # Reusable components
│   ├── navbar.html
│   └── footer.html
│
└── README.md
```

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   ```

2. **Navigate to the project**:
   ```bash
   cd portfolio
   ```

3. **Customize the content**:
   - Open `index.html` and update your name and information
   - Replace placeholder images in `assets/images/`
   - Update the resume in `assets/resume/`
   - Modify contact information in `contact.html`

4. **View the website**:
   - Open `index.html` in your browser
   - Or use a local server:
     ```bash
     # Python
     python -m http.server
     
     # Node.js
     npx serve
     ```

## Customization

### Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #3498db;
    --secondary-color: #2ecc71;
    --dark-color: #2c3e50;
    /* Add more colors as needed */
}
```

### Fonts
Change the font family in `css/style.css`:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Projects
Add more projects in `projects.html`:
```html
<div class="project-card" data-category="web">
    <img src="assets/images/your-project.png" alt="Project Name">
    <div class="project-overlay">
        <div class="project-info">
            <h3>Your Project</h3>
            <p>Description</p>
            <!-- Add links -->
        </div>
    </div>
</div>
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with variables and animations
- **JavaScript**: Interactive features
- **Font Awesome**: Icons (via CDN)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Your Name - [Your Website](https://yourwebsite.com)

## Acknowledgments

- [Font Awesome](https://fontawesome.com) for icons
- [Google Fonts](https://fonts.google.com) for typography
- [Unsplash](https://unsplash.com) for placeholder images
