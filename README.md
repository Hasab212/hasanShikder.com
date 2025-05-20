# 3D Personal Portfolio Website

A modern, responsive personal portfolio website featuring 3D animations and effects, built with pure HTML, CSS, and JavaScript.

## Features

- 🎨 Clean, modern design with light/dark theme support
- 🌟 Smooth 3D animations and transitions
- 📱 Fully responsive layout
- 🎯 Interactive elements with hover effects
- 🌓 Automatic theme detection based on system preferences
- ⚡ GPU-accelerated animations for optimal performance

## Sections

1. **Hero Section**
   - Animated 3D background with floating cubes
   - Glitch text effect on name
   - Smooth parallax effect

2. **About Section**
   - 3D flip effect on profile image
   - Responsive layout

3. **Skills Section**
   - Interactive 3D flip cards
   - Hover animations
   - Clean grid layout

4. **Projects Section**
   - 3D project cards with flip effect
   - Image thumbnails
   - Project details on hover

5. **Contact Section**
   - Animated form inputs
   - Form validation
   - Success feedback

6. **Social Links**
   - Animated icons
   - 3D rotation effect on hover

## Technical Details

- Built with vanilla HTML5, CSS3, and JavaScript (ES6+)
- No external libraries or frameworks
- Uses CSS variables for theming
- Implements Intersection Observer for scroll animations
- GPU-accelerated animations using transform3d
- Responsive design using CSS Grid and Flexbox

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd portfolio-website
   ```

3. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

## Customization

1. **Personal Information**
   - Update the content in `index.html`
   - Replace placeholder images in the `assets` folder
   - Modify social media links

2. **Styling**
   - Edit CSS variables in `css/style.css` for theme colors
   - Adjust animation timings and effects
   - Modify layout breakpoints for responsive design

3. **JavaScript**
   - Customize animations in `js/main.js`
   - Add additional interactive features
   - Modify form handling logic

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized animations using transform3d
- Lazy loading for images
- Minimal DOM manipulation
- Efficient event handling

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details. 