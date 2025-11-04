# Durvas Harkulkar - Portfolio Website

A modern, professional, and minimalistic portfolio website featuring both light and dark themes with a clean UI design.

## Features

- 🌓 **Light/Dark Theme Toggle** - Switch between light and dark modes
- 📱 **Fully Responsive** - Optimized for all device sizes
- 🎨 **Modern Design** - Clean, professional UI with teal accent color
- ⚡ **Smooth Animations** - Interactive elements with smooth transitions
- 📄 **Complete Sections** - Home, About, Education, Experience, Projects, Skills, Achievements, Contact
- 🏆 **Achievements Gallery** - Separate page for certificates and accomplishments
- 📧 **Contact Form** - Functional contact form with validation
- 🧭 **Dynamic Navigation** - Smooth scrolling and active link highlighting

## Sections Overview

### Home
- Circular profile image
- Professional introduction
- Call-to-action buttons
- Theme toggle button

### About
- Personal bio and background
- Academic journey
- Professional experience
- Personal interests and strengths

### Education
- Timeline view of academic achievements
- Current B.Tech at JSPM RSCOE (CGPA: 8.64)
- Diploma from Pimpri Chinchwad Polytechnic (89.31%)
- Secondary school from Amrita Vidyalayam (85.80%)

### Experience
- KPIT Technologies internship details
- Software testing and embedded systems
- ISTQB concepts and CANoe tool experience

### Projects
- User-Specific To-Do List (DBMS Project)
- Bank Registration System
- FootSparx E-Commerce Website

### Skills
- Programming Languages: C, C++, Java, Python
- Web Technologies: HTML, CSS, JavaScript, PHP
- Database: DBMS, SQLite, MongoDB
- Tools: CANoe, XAMPP, GitHub
- Languages: English, Marathi, Hindi, German (A1)

### Achievements
- Separate page with certificate gallery
- Category filtering (Academic, Technical, Extra-Curricular)
- Modal view for detailed certificate viewing
- Upload functionality for new achievements

### Contact
- Contact form with validation
- Social media links
- Professional contact information

## Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript** - Interactive functionality
- **Font Awesome** - Icons
- **Google Fonts** - Poppins font family

### Key Features
- CSS Variables for theme management
- Intersection Observer for animations
- Local Storage for theme persistence
- Responsive grid layouts
- Smooth scrolling navigation
- Form validation
- Image modal system

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Setup Instructions

1. **Download/Clone** the project files
2. **Open** `index.html` in your web browser
3. **Customize** the content as needed:
   - Replace placeholder profile image
   - Update contact information
   - Add real project links
   - Upload actual certificates to achievements page

## Customization

### Changing Colors
The website uses CSS variables for easy color customization. Edit the `:root` section in `styles.css`:

```css
:root {
    --primary-color: #2C5F2D;    /* Main accent color */
    --primary-light: #4A7C59;    /* Lighter shade */
    --primary-dark: #1A3D1B;     /* Darker shade */
    /* ... other variables */
}
```

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Update navigation menu
4. Add smooth scrolling functionality in `script.js`

### Profile Image
Replace the placeholder image URL in `index.html`:
```html
<img src="path/to/your/image.jpg" alt="Durvas Harkulkar" id="profile-img">
```

## File Structure

```
durvas-portfolio/
├── index.html          # Main portfolio page
├── achievements.html    # Achievements gallery page
├── styles.css          # All styling and themes
├── script.js           # Interactive functionality
└── README.md           # This file
```

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for fast loading
- Responsive images
- Smooth animations with hardware acceleration
- Lazy loading for better performance

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- High contrast ratios
- Screen reader friendly

## Future Enhancements

- [ ] Add blog section
- [ ] Implement contact form backend
- [ ] Add project demo links
- [ ] Include testimonials section
- [ ] Add resume download functionality
- [ ] Implement search functionality
- [ ] Add multi-language support

## Contact Information

- **Email**: harkulkardurvas18@gmail.com
- **LinkedIn**: Durvas Harkulkar
- **GitHub**: Durvas18
- **Instagram**: durvas_18

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: This portfolio website is designed to showcase Durvas Harkulkar's skills, experience, and achievements in a professional and modern way. The design emphasizes clean aesthetics, user experience, and technical proficiency.
