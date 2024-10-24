# Munamii Cakery Website

A responsive website for Munamii Cakery, showcasing their collection of wedding cakes and cupcakes. The site features a clean, modern design with an emphasis on visual presentation and user experience.

## Features

- Responsive design that works across desktop and mobile devices
- Product showcase with hover effects
- Newsletter subscription functionality
- Contact form
- Social media integration
- Image optimization for fast loading
- Custom color scheme with CSS variables

## Project Structure

```
munamii-cakery/
├── index.html          # Homepage
├── products.html       # Product catalog
├── about.html         # About page
├── contact.html       # Contact information
├── emailform.html     # Contact form
├── style.css          # Main stylesheet
├── images/
│   ├── logo.png
│   ├── Cakes/        # Wedding cake images
│   │   ├── T1.png
│   │   ├── T2.png
│   │   └── ...
│   └── CupCakes/     # Cupcake images
│       ├── CC1.png
│       ├── CC2.png
│       └── ...
```

## Technical Specifications

### CSS Variables

The site uses CSS custom properties for consistent theming:

```css
--primary-color: #c34400
--primary-light: #e67e22
--primary-dark: #8f3200
--secondary-color: #e67e22
--background-color: #f0d0d0
--text-color: #2a2a2a
```

### Typography

- Primary Font: 'Poiret One'
- Fallback: cursive

### Responsive Breakpoints

- Mobile: up to 480px
- Tablet: up to 768px
- Desktop: 769px and above

## Setup Instructions

1. Clone the repository
2. Ensure all image assets are placed in their respective directories
3. Open `index.html` in a web browser to view the site

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Features & Functionality

### Product Display
- Circular image display with hover effects
- Price and product information overlay
- Responsive grid layout

### Contact Form
- Name field
- Email field
- Message textarea
- Form validation
- Success/error message display

### Newsletter Subscription
- Email input field
- Subscribe button
- Footer integration

## Development Notes

### CSS Organization
- Variables for theming
- Modular component styles
- Media queries for responsive design
- Hover effects and transitions

### Best Practices
- Semantic HTML5 elements
- Responsive images
- Accessibility considerations
- Mobile-first approach

## Maintenance

To update product information:
1. Add new product images to the respective folders (Cakes/ or CupCakes/)
2. Update the product listings in `products.html`
3. Ensure images are optimized for web use

## License

© 2023 Munamii Cakery. All rights reserved.

## Contact Information

- Instagram: [@munamiicakery](https://www.instagram.com/munamiicakery/)
- Facebook: [Munamii Cakery](https://www.facebook.com/p/munamiicakery-100068077487468/)
- Email: info@munamiicakery.com
