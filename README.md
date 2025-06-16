# Kyara Beverages Website

A responsive, modern website for Kyara Beverages showcasing their innovative millet-based fruit drinks.

## Project Overview

This website was developed to reflect Kyara Beverages' brand ethos: fresh, authentic, and user-centric. The site serves as a digital storefront for their line of millet-based fruit drinks, combining traditional ingredients with innovative production methods.

### Key Requirements Met

✅ **Simple Homepage**: Created a clean, engaging static homepage  
✅ **Responsive Design**: Implemented fully responsive layout across all screen sizes  
✅ **Code Organization**: Maintained clear file structure with well-commented code  
✅ **Brand Representation**: Captured Kyara's fresh, authentic ethos through design choices  

## Core Features

### 1. Responsive Design Implementation

The website is fully responsive with specific optimizations for:

- **Mobile (≤480px)**: Compact layout with optimized navigation and content flow
- **Tablet (481px-1023px)**: Adaptive layout with properly scaled components
- **Desktop (≥1024px)**: Full-featured experience with enhanced visual elements

Media queries strategically implement breakpoints for a seamless user experience across all devices. The hero section features optimized background positioning for different screen sizes to prevent image distortion.

### 2. Advanced Front-End Techniques

- **Lazy Loading**: Implemented JavaScript-based image lazy loading using IntersectionObserver API to improve page performance
- **Smooth Scrolling**: Enhanced navigation with smooth scroll behavior
- **Animation Effects**: Used AOS (Animate On Scroll) library for subtle, engaging animations
- **Custom CSS Variables**: Employed CSS custom properties for consistent theming
- **Responsive Typography**: Implemented fluid typography for optimal readability

### 3. Site Structure

The website includes all required sections:

- **Hero Section**: Features Kyara's logo, tagline ("Refreshment, Reimagined"), and an optimized background image
- **About Section**: Provides concise messaging about Kyara's mission and values
- **Product Showcase**: Displays three featured drinks with images, names, and descriptions
- **Contact Form**: Includes name, email, and message fields with basic validation

## Technologies Used

- **HTML5**: Semantic markup for improved accessibility and SEO
- **CSS3**: Modern styling techniques including flexbox, CSS Grid, and custom properties
- **JavaScript**: Enhanced interactivity, form validation, and lazy loading
- **Font Awesome**: Scalable vector icons
- **Google Fonts**: Typography using Poppins and Montserrat fonts
- **AOS Library**: Scroll-based animations

## How to View Locally

### Method 1: Direct Browser Opening

1. Clone or download the repository
2. Open `index.html` in any modern web browser

### Method 2: Using a Local Server (Recommended)

For the best experience, especially to test features like lazy loading:

```bash
# Using VS Code with Live Server extension
# 1. Install the "Live Server" extension
# 2. Right-click on index.html and select "Open with Live Server"

# OR using Python's built-in server
python -m http.server 5500

# OR using Node.js
npx serve
```

Then navigate to `http://localhost:5500` in your browser.

## Deployment Status

This website has been successfully deployed to GitHub:

- **Repository**: [https://github.com/charan22640/Kyara-Beverages](https://github.com/charan22640/Kyara-Beverages)
- **Live Website**: [https://charan22640.github.io/Kyara-Beverages/](https://charan22640.github.io/Kyara-Beverages/)

### GitHub Pages Configuration

To ensure your website is live:

1. Go to the repository settings on GitHub: [Repository Settings](https://github.com/charan22640/Kyara-Beverages/settings)
2. Navigate to "Pages" in the sidebar
3. Under "Source", confirm "main" branch and "/ (root)" folder are selected
4. Click "Save" if needed

> **Note**: It may take a few minutes for changes to appear after GitHub Pages is enabled.

### Making Future Updates

To update your website in the future:

```bash
# Pull the latest changes (if working from a different computer)
git pull

# Make your changes to the files

# Commit and push changes
git add .
git commit -m "Update website"
git push
```

After pushing updates, the live site will automatically refresh in a few minutes.

## Project Structure

```
Kyara Beverages/
├── index.html           # Main HTML file
├── image-test.html      # Image testing utility
├── css/
│   └── styles.css       # Main stylesheet with responsive design
├── js/
│   └── main.js          # JavaScript functionality including lazy loading
├── images/              # Optimized image assets
│   ├── logo.png         # Brand logo
│   ├── wave-shape.svg   # Decorative elements
│   ├── placeholder/     # Placeholder images for lazy loading
│   └── product-images/  # Product photography
└── README.md            # Project documentation
```

## Development Highlights

### Optimization Techniques

- **Image Optimization**: Implemented lazy loading with placeholders to improve page load speed
- **Responsive Images**: Ensured images scale appropriately across devices without distortion
- **CSS Organization**: Structured CSS with clear comments and logical grouping
- **JavaScript Performance**: Used modern JavaScript features with fallbacks for browser compatibility

### Design Decisions

- **Color Palette**: Employed natural greens and earth tones to emphasize freshness and organic ingredients
- **Typography Hierarchy**: Used Montserrat for impactful headings and Poppins for readable body text
- **Whitespace Utilization**: Strategic use of whitespace for improved readability and focus
- **Visual Consistency**: Maintained consistent design language throughout all sections

## Completion of Requirements

This project successfully fulfills all requirements from the provided task brief:

1. **Simple Homepage**: Created with all required sections
2. **Responsive Design**: Fully implemented across all screen sizes
3. **Code Organization**: Clear structure with comprehensive documentation
4. **Brand Representation**: Design choices align with Kyara's fresh, authentic, and user-centric ethos

---

*This website was developed as part of an internship application for Kyara Beverages. The project demonstrates proficiency in front-end web development with a focus on responsive design, performance optimization, and brand-aligned user experience.*
