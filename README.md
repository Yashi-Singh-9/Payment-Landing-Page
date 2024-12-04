# Payment Landing Page

This is a responsive payment landing page designed as part of a **Frontend Pro coding challenge**. The page promotes a modern and intuitive credit card service, emphasizing daily convenience and savings.

## Live Demo

View the live project [here](https://yashi-singh-9.github.io/Payment-Landing-Page/).

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Responsive Design](#responsive-design)
- [File Structure](#file-structure)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Responsive Navigation:** Includes a fully responsive menu with a **hamburger icon** for mobile devices.
- **Modern Design:** Follows a minimalistic, visually appealing design with soft violet accents and clean fonts.
- **Interactive Elements:** Buttons and navigation links feature smooth hover effects.
- **Mobile-Friendly:** Optimized for various screen sizes, including desktops, tablets, and smartphones.

## Technologies Used

- **HTML5**: For the structure of the page.
- **LESS (CSS Preprocessor)**: For modular, maintainable CSS code with variables and nesting.
- **JavaScript**: For interactivity, such as the mobile menu functionality.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Yashi-Singh-9/Payment-Landing-Page.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Payment-Landing-Page
   ```
3. Compile the LESS file into CSS:
   - If you don’t have LESS installed, first install it via npm:
     ```bash
     npm install -g less
     ```
   - Compile the `style.less` file to `style.css`:
     ```bash
     lessc style.less style.css
     ```
4. Open the `index.html` file in your browser to view the project.

## Responsive Design

The landing page is optimized for multiple screen sizes:
- **Desktop:** Horizontal layout with navigation and content aligned side-by-side.
- **Tablet:** Compact layout with reduced gaps and a visible hamburger menu.
- **Mobile:** Vertical stacking of elements, with the menu accessible through a hamburger icon.

## File Structure

```
Payment-Landing-Page/
├── index.html          # Main HTML file
├── style.less          # LESS source file for styles
├── style.css           # Compiled CSS file
├── script.js           # JavaScript for interactivity
├── images/             # Folder for images (logo, icons, and mockups)
├── README.md           # Documentation (this file)
```

## How It Works

1. **Header Navigation**:
   - Displays links to sections like Features, Pricing, Help, Blog, and About Us.
   - Includes **Log In** and **Sign Up** buttons with hover effects.
   - Fully collapses into a hamburger menu on smaller screens.

2. **Main Content**:
   - Features a tagline, main heading, and a download button with a smooth hover transition.
   - Showcases a **mobile app UI mockup** to visually convey the product’s features.

3. **Responsive Hamburger Menu**:
   - Controlled using JavaScript: toggles visibility of navigation links.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch and submit a pull request.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.
