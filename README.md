# Wanderlust Travels - Travel Agency Landing Page

## Overview
A professional, fully responsive travel agency landing page built with Bootstrap 5 components. The page showcases travel destinations, tour packages, and provides a contact form for inquiries.

## Features Implemented

### 1. **Navigation Bar**
- Sticky navbar with agency branding ("Wanderlust Travels" with globe icon)
- Responsive navigation links (Home, Destinations, Tours, Contact)
- Smooth scrolling to sections
- Mobile-friendly hamburger menu

### 2. **Hero Section**
- Full-screen hero with background image
- Overlay for text readability
- Prominent heading, subheading, and dual CTA buttons
- Smooth animations and transitions
- Responsive design for all screen sizes

### 3. **Destinations Section**
- Grid layout displaying 6 travel destinations:
  - Paris, France
  - Bali, Indonesia
  - New York, USA
  - Tokyo, Japan
  - Sydney, Australia
  - Rome, Italy
- Bootstrap cards with:
  - High-quality images from Unsplash
  - Destination titles and descriptions
  - Category badges (Popular, Affordable, Adventure, etc.)
  - "Learn More" buttons
  - Hover effects with smooth transitions
  - Responsive grid (4 columns on large screens, 2 on tablets, 1 on mobile)

### 4. **Tours Section**
- Bootstrap Accordion component with 5 tour packages:
  - European Grand Tour (14 days, $2,499)
  - Southeast Asia Adventure (10 days, $1,399)
  - New Zealand Nature Expedition (12 days, $1,899)
  - Caribbean Cruise (7 days, $999)
  - Ancient Wonders Tour (9 days, $1,699)
- Each package includes:
  - Icons (FontAwesome) for visual appeal
  - Pricing information
  - Included features
  - "View Details & Book" links
  - First item expanded by default

### 5. **Contact Form**
- Comprehensive form with:
  - Full Name field (required)
  - Email Address field (required)
  - Destination dropdown (required)
  - Phone Number field (optional)
  - Message textarea (required)
  - Newsletter subscription checkbox
- Bootstrap form validation
- Responsive layout
- Large, accessible form controls
- Submit button with hover effects

### 6. **Footer**
- Three-column layout:
  - Company info and description
  - Quick links navigation
  - Social media icons (Facebook, Twitter, Instagram, YouTube, LinkedIn)
- Copyright information
- Footer links for Privacy Policy, Terms of Service, and Sitemap
- Smooth hover effects on links and icons

## Technical Details

### Bootstrap Components Used
- Navbar with collapse/responsive functionality
- Grid system (container, row, col-lg, col-md, col-sm)
- Cards with shadows
- Accordion for tour packages
- Form controls and validation
- Badges for categorization
- Buttons with various styles
- Responsive utilities

### Custom CSS Styling
- **Colors**: Primary blue (#0d6efd), dark backgrounds, gradient overlays
- **Typography**: Bold headings, readable body text, proper hierarchy
- **Animations**: Fade-in-up, hover effects, smooth transitions
- **Responsive Design**: Mobile-first approach with breakpoints for all devices
- **Accessibility**: Proper contrast ratios, semantic HTML, form validation

### Responsive Breakpoints
- Desktop (1200px+): Full multi-column layouts
- Tablet (768px - 1199px): 2-column grid
- Mobile (576px - 767px): Stacked layouts
- Extra small (<576px): Full-width single column

## File Structure
```
Project HTML/
├── index.html          # Main HTML file
├── index.css           # Custom styling
├── style.css           # (Old file, can be removed)
├── hello.txt          # (Placeholder file)
└── README.md          # This file
```

## Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features
- Optimized images from CDN
- External CDN resources for Bootstrap and FontAwesome
- Smooth scrolling behavior
- Hardware-accelerated animations
- Minimal custom CSS for faster load times

## Customization Guide

### Change Colors
Edit the CSS variables in `index.css`:
```css
:root {
    --primary-color: #0d6efd;
    --secondary-color: #6c757d;
    /* etc. */
}
```

### Update Destinations
Edit the destination cards in `index.html`:
- Change image URLs
- Update titles and descriptions
- Modify badge colors and text

### Modify Tour Packages
Edit the accordion items in `index.html`:
- Update prices
- Change included features
- Modify duration and destinations

### Add Social Media Links
Update the footer social icons in `index.html`:
- Replace `href="#"` with actual social media URLs

## Testing Recommendations
1. **Responsive Testing**: Test on various screen sizes (desktop, tablet, mobile)
2. **Browser Testing**: Verify in all major browsers
3. **Form Validation**: Test form submission and validation
4. **Accessibility**: Check keyboard navigation and screen reader compatibility
5. **Performance**: Check load times and optimize images if needed

## Future Enhancements
- Add a backend for form submission
- Implement image galleries for each destination
- Add booking functionality
- Integrate payment gateway
- Add blog/travel tips section
- Implement multi-language support
- Add testimonials section
- Implement search functionality
- Add map integration for destinations

## Credits
- **Bootstrap**: Frontend framework
- **FontAwesome**: Icon library
- **Unsplash**: Free stock images
- **Google Fonts**: Typography (via Bootstrap)

## License
This project is ready to use and can be modified as needed for your travel agency.
