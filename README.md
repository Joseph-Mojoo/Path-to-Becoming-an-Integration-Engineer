# Path to Becoming an Integration Engineer

## Description

This project is an interactive presentation that outlines the path to becoming an Integration Engineer. It's designed as a single-page web application that guides users through a series of slides, each detailing different aspects of the Integration Engineering career path.

## Features

- Interactive slide presentation with 7 informative slides
- Responsive design for various screen sizes
- Animated transitions between slides
- Keyboard navigation support (arrow keys)
- Dynamic content rendering
- Stylish UI with glassmorphism effect and gradient background
- Fireworks animation on the final slide
- SPARC logo watermark with animation

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome 6.0.0-beta3 for icons
- Google Fonts (Montserrat and Roboto Slab)
- Fireworks.js for the fireworks animation

## Setup

1. Clone the repository to your local machine.
2. Ensure you have the `sparc_logo.png` image in the same directory as the `index.html` file.
3. Open the `index.html` file in a modern web browser.

## Usage

- Use the "Previous" and "Next" buttons to navigate through the slides.
- Alternatively, use the left and right arrow keys for navigation.
- The current slide number and total number of slides are displayed at the bottom of the screen.

## Customization

To modify the content of the presentation:

1. Open the `index.html` file in a text editor.
2. Locate the `slides` array in the JavaScript section.
3. Edit, add, or remove slide objects as needed.
4. Each slide object should follow this structure:
   ```javascript
   {
     title: "Slide Title",
     subtitle: "Slide Subtitle",
     content: [
       {icon: "fas fa-icon-name", text: "Content item"},
       // Add more content items as needed
     ]
   }
   ```
5. For special slides (intro and last), use the `isIntroSlide` or `isLastSlide` property.

## Responsive Design

The presentation is designed to be responsive and works well on various screen sizes:
- Desktop: Full-width presentation with larger fonts and spacing
- Tablet: Adjusted layout with slightly reduced font sizes
- Mobile: Compact layout with further reduced font sizes and adjusted spacing

## Accessibility

- The presentation supports keyboard navigation for better accessibility.
- High contrast colors are used for better readability.
- Font sizes are responsive and maintain readability on different devices.

## Performance

- The presentation uses CSS animations for smooth transitions.
- External resources (Font Awesome, Google Fonts) are loaded from CDNs for faster loading.
- The Fireworks.js library is loaded only when needed (on the last slide).

## Browser Compatibility

This presentation is designed to work on modern browsers that support CSS3 and ES6+ JavaScript features. It has been tested on:
- Google Chrome (latest version)
- Mozilla Firefox (latest version)
- Safari (latest version)
- Microsoft Edge (Chromium-based, latest version)

## License

[Add your chosen license here]

## Author

Presented by Joseph Mojoo

## Acknowledgements

- SPARC for the logo and inspiration
- Font Awesome for the icons
- Google Fonts for the typography
- Fireworks.js for the fireworks animation
