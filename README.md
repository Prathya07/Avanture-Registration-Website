A-World Adventure Travel Website
A fully responsive, animated travel and adventure website built with HTML, CSS, and vanilla JavaScript. This project showcases modern web design techniques including custom cursors, scroll-triggered animations, hover effects, and video integration.
Live Demo
View Live Site (Add your deployment link here)
Screenshots
screenshot-home.png
screenshot-services.png
Features
Sections
Table
Section	Description
Hero / Home	Full-screen landing with waterfall background, logo, navigation, and call-to-action
About Us	Split-layout with text content and adventure imagery
Services	Three-card grid showcasing Rafting, Hiking, and Camping
Video	Background video section with modal popup player
Testimonial	Customer review card with author profile
Why Choose Us	Feature highlight with contact CTA banner
Footer	Email subscription, contact info with icons
Animations & Effects
Custom Mountain Cursor — 80px mountain image follows mouse movement, scales on hover over interactive elements
Scroll Reveal — Elements fade and slide into view using Intersection Observer API
3D Card Tilt — Service cards tilt based on mouse position using CSS perspective
Button Ripple — Click ripple effect on all CTA buttons
Parallax Footer — Subtle parallax scrolling on footer background
Pulse Animation — Play button with continuous pulse glow effect
Wave Separators — SVG wave transitions between sections
Hover Effects
Navigation underline slide-in
Image zoom and rotation
Card lift with shadow expansion
Color transitions to brand purple (#3d2b8c)
Icon scale and rotation
Tech Stack
HTML5 — Semantic structure
CSS3 — Flexbox, Grid, Custom Properties, Keyframe Animations
JavaScript (ES6) — Intersection Observer, Event Listeners, DOM Manipulation
No frameworks — Pure vanilla code for maximum performance
Project Structure
plain
a-world-website/
├── index.html          # Main HTML file
├── README.md           # Project documentation
└── assets/
    ├── css/
    │   └── style.css   # Stylesheets (embedded in HTML for single-file deployment)
    ├── js/
    │   └── main.js     # JavaScript (embedded in HTML)
    └── images/         # Screenshots and previews
Getting Started
Prerequisites
Any modern web browser (Chrome, Firefox, Safari, Edge)
Installation
Clone the repository
bash
git clone https://github.com/yourusername/a-world-adventure.git
Navigate to project directory
bash
cd a-world-adventure
Open index.html in your browser
bash
open index.html
OR simply double-click the file
Usage
Move your mouse to see the custom mountain cursor
Scroll down to trigger section animations
Hover over cards, buttons, and images for interactive effects
Click the play button in the Video section to open the modal
Use navigation links for smooth scrolling between sections
Browser Support
Table
Browser	Version
Chrome	90+
Firefox	88+
Safari	14+
Edge	90+
Performance
Single-file deployment option (all CSS/JS embedded)
Optimized images via Unsplash CDN
Hardware-accelerated animations using transform and opacity
Lazy loading ready for production deployment
Customization
Changing Colors
Edit CSS custom properties in the <style> section:
css
:root {
  --primary: #3d2b8c;
  --dark: #1a1a2e;
  --light: #ffffff;
}
Adding More Services
Duplicate the .service-card div inside .services-grid:
HTML
<div class="service-card reveal-scale">
    <div class="service-image-wrapper">
        <img src="your-image.jpg" alt="Service Name" class="service-image">
    </div>
    <button class="service-btn btn-rafting">Service Name</button>
</div>
Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
Distributed under the MIT License. See LICENSE for more information.
Acknowledgments
Images from Unsplash
Video from Mixkit
Icons from SVG path data
Design inspiration from adventure travel themes
Contact
Your Name - @yourtwitter - email@example.com
Project Link: https://github.com/yourusername/a-world-adventure
AI Development Note
This website was developed with the assistance of AI (Kimi K2.6 by Moonshot AI). The AI helped generate the complete HTML/CSS/JS codebase, design the layout based on UI screenshots, implement animations and hover effects, and structure the responsive grid system. All visual elements, transitions, and interactive features were co-created through human-AI collaboration.
