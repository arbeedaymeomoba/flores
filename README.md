# Flores Skincare Landing Page

Flores is a skincare-focused e-commerce landing page built with semantic HTML and CSS. It presents a calm, editorial visual style for a beauty brand, with product highlights, brand information, blog content, an email subscription area, a social image gallery, and a centered footer.

## Overview

The page is designed as a front-end practice project for building a polished product landing page without a framework or build tool. It uses locally stored product and lifestyle images, custom layout styles, and Font Awesome icons loaded from a CDN.

## Features

- Navigation bar with brand logo, page links, account, search, and cart icons
- Hero section with skincare messaging and a shop call-to-action
- Service highlights for delivery, store pickup, packaging, and returns
- About section with brand mission copy and a read-more button
- Trending products section with product images, names, prices, carousel indicators, and testimonial navigation
- Latest drops section featuring additional products
- Recent blogs section with article previews and a read-blogs button
- Subscription section with an email address field and submit icon
- Six-image social gallery using skincare and lifestyle photography
- Footer with Flores branding, navigation links, and social media icons
- Responsive gallery and footer layouts for smaller screens

## Technologies

- HTML5
- CSS3
- Font Awesome 6.4.0 via CDN

No package manager, framework, compiler, or JavaScript dependency is required.

## Project Structure

```text
flores/
├── index.html          # Main landing page markup
├── style.css           # Layout, typography, colors, and responsive styles
├── script.js           # Reserved for future interactivity
├── README.md           # Project documentation
└── assets/
	└── images/         # Hero, product, blog, and gallery images
```

## Running the Project

### Option 1: Open directly

1. Open the `flores` folder.
2. Double-click `index.html`.
3. The page will open in your default browser.

### Option 2: Use VS Code Live Server

1. Open the project folder in VS Code.
2. Install the **Live Server** extension if it is not already installed.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

Using a local server is recommended while editing because it provides automatic browser refresh and a consistent development environment.

## Customization

### Change page content

Edit `index.html` to update:

- Product names and prices
- Hero and about copy
- Blog titles and descriptions
- Navigation destinations
- Footer social links

### Change the visual design

Edit `style.css` to adjust:

- Colors and backgrounds
- Typography and heading sizes
- Section spacing
- Product and gallery layouts
- Button and icon states
- Mobile breakpoints

### Add functionality

`script.js` is currently empty. It can be used to add:

- Working product carousels
- Shopping cart behavior
- Search and account interactions
- Form validation and subscription handling
- Mobile navigation controls

The current buttons and social links are visual controls or placeholder links and do not connect to a back-end service.

## Assets

All project images are stored in `assets/images`. When adding new images:

- Use descriptive filenames.
- Keep image paths relative to `index.html`.
- Add meaningful `alt` text for accessibility.
- Optimize large images before adding them to the project.

The Font Awesome stylesheet is loaded from the internet, so the icons require an active internet connection unless the dependency is replaced with a local copy.

## Accessibility Notes

The page includes document language metadata, viewport settings, descriptive image alternatives, navigation labels, and accessible labels for icon-only controls. Future improvements could include keyboard behavior for carousel buttons and a success or error message for the subscription form.

## Browser Support

The project uses standard HTML and CSS features supported by current versions of Chrome, Edge, Firefox, and Safari. Test the layout at both desktop and mobile widths after making major style changes.

## Author

Created as a Flores skincare landing-page project by Sarum Usman.
