#  Responsive Portfolio Website

[Project Preview](https://simple-portfolio-tan-psi.vercel.app/)

> **Acknowledgement**: This project was adapted from [Bedimcode's Responsive Portfolio Website tutorial](https://www.youtube.com/watch?v=27JtRAI3QO8) and their [GitHub repository](https://github.com/bedimcode/responsive-portfolio-website). Significant modifications have been made to the original work.

A modern, responsive portfolio website designed with a mobile-first approach, featuring smooth animations, dark theme, and contact form functionality.

## Features

- **Responsive Design**: Works seamlessly on all devices from mobile to desktop
- **Dark Theme**: Beautiful dark UI with customizable accent colors
- **Animations**: Smooth scroll-triggered animations throughout the site
- **Smooth Scrolling**: Elegant navigation between sections
- **Contact Form**: Functional email sending capability
- **Mobile-First**: Developed with mobile-first methodology
- **Cross-Browser Compatibility**: Tested on major browsers

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- JavaScript (ES6+)
- [EmailJS](https://www.emailjs.com/) (for contact form functionality)
- [ScrollReveal](https://scrollrevealjs.org/) (for scroll animations)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AmanVerma1067/Simple_Portfolio
   ```

2. Navigate to the project directory:
   ```bash
   cd Simple_Portfolio
   ```

3. Open `index.html` in your browser or deploy to your preferred hosting service.

## Customization

To change the accent color:
1. Open `assets/css/style.css`
2. Modify the CSS variables in the `:root` selector:
   ```css
   :root {
       --main-color: #3a6cf4; /* Change this to your preferred color */
       --hover-color: #2a56d1;
       /* Other custom properties */
   }
   ```

## Contact Form Setup

To enable the email sending functionality:

1. Sign up for [EmailJS](https://www.emailjs.com/)
2. Create an email template and service
3. Update the EmailJS configuration in `assets/js/script.js`:
   ```javascript
   emailjs.init('YOUR_USER_ID');
   const serviceID = 'YOUR_SERVICE_ID';
   const templateID = 'YOUR_TEMPLATE_ID';
   ```

## License
This project is licensed under the MIT License. Note that this license applies only to my modifications. The original work remains copyright of Bedimcode.


