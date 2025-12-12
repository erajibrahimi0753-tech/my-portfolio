# Eraj Ibrahimi - Portfolio Website

A modern, responsive portfolio website showcasing the professional experience, education, and achievements of Eraj Ibrahimi.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Smooth Scrolling**: Enhanced navigation experience
- **Interactive Elements**: Hover effects and scroll animations
- **Mobile-Friendly Navigation**: Hamburger menu for mobile devices

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla JS)
- Google Fonts (Inter)

## Getting Started

### Prerequisites

No special prerequisites needed. Just a modern web browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to use.

### Local Development

If you want to run it with a local server (recommended):

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    /* ... */
}
```

### Adding Your Photo

Replace the placeholder SVG in the hero section with your actual photo:

```html
<div class="hero-image">
    <img src="path/to/your/photo.jpg" alt="Eraj Ibrahimi" class="profile-photo">
</div>
```

Then add CSS for `.profile-photo`:

```css
.profile-photo {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px solid rgba(255, 255, 255, 0.3);
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.

## Contact

- **Email**: eraj.ibrahimi0753@gmail.com
- **Phone (Afghanistan)**: +93 782614416
- **Phone (China)**: +86 16679306024

