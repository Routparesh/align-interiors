# Align Interiors - Premium Interior Design Website

## Overview
A fully responsive, single-page website for **Align Interiors**, a professional interior design studio in Pune, Maharashtra. The website features an editorial aesthetic with premium design elements, smooth animations, and complete functionality.

## File Structure
- `align-interiors.html` - Complete website (single HTML file)
- `ALIGN_INTERIORS_README.md` - This documentation file

## Features

### Design Elements
- **Premium Editorial Layout** - Full-width sections with generous white space
- **Refined Color Palette** - Warm architectural neutrals with muted brass accents
- **Architectural Typography** - Georgia serif for headings, clean system-ui for body
- **Dark/Light Theme** - Automatic theme switching based on user preference
- **Responsive Design** - Fully responsive from mobile to desktop
- **No External Dependencies** - All CSS/JS inline (no CDNs, CSP-compliant)

### Functional Components
1. **Sticky Navigation** with mobile hamburger menu
2. **Full-viewport Hero Section** with gradient backgrounds
3. **About Section** - Split-screen editorial layout
4. **Services Section** - 5 premium service cards in responsive grid
5. **Design Philosophy** - Dark section with 3-step approach
6. **Portfolio Gallery** - Masonry-style grid with hover effects
7. **Why Us Section** - 5 differentiators with brass accents
8. **Process Timeline** - Step-by-step design process
9. **Testimonials** - Placeholder cards for client reviews
10. **Location Section** - Embedded Google Maps + contact info
11. **Contact Form** - Validated consultation request form
12. **Sophisticated Footer** - 3-column layout with all business details

### Technical Features
- **Mobile-First Responsive Design** - Fully optimized for all screen sizes
- **Scroll Reveal Animations** - Elements fade in smoothly as you scroll
- **Form Validation** - Real-time validation with error/success states
- **Smooth Scrolling** - All navigation links animate smoothly
- **Click-to-Call Functionality** - Direct phone link (+91 97660 45538)
- **Google Maps Integration** - Location map with directions link
- **Accessibility** - ARIA labels, keyboard navigation, reduced motion support
- **Performance Optimized** - No external requests, fast loading

## Business Information Included

### Contact Details
- **Business Name:** Align Interiors
- **Address:** Estonia Office No. 504-B, Gulawani Maharaj Road, opposite to Mehendale Garage, Erandwane, Pune, Maharashtra 411004
- **Phone:** +91 97660 45538
- **Google Business Profile:** https://maps.app.goo.gl/5FdStZSszySKSZ8L6

### SEO Metadata
- **Title:** Align Interiors | Interior Designers in Pune
- **Description:** Align Interiors creates thoughtful, functional and elegant residential and commercial interiors in Pune, Maharashtra. Book a consultation today.

## How to Use

### View the Website
Simply open `align-interiors.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

### Test Responsiveness
1. Open the site in desktop browser
2. Use Developer Tools (F12) to toggle device toolbar
3. Test various screen sizes (mobile, tablet, desktop)

### Test Features
- **Mobile Menu:** Click hamburger icon on mobile/tablet screens
- **Form Validation:** Try submitting incomplete contact form
- **Smooth Scrolling:** Click any navigation link
- **Theme Switching:** Change your OS/system theme preference
- **Click-to-Call:** Click phone number (will open phone dialer on mobile)

## Customization Guide

### Replace Placeholder Content

#### 1. Portfolio Images
Currently using CSS gradient placeholders. Replace with actual project photos:
```html
<!-- In portfolio section, replace .project-item background with actual images -->
<div class="project-item" style="background: url('your-image.jpg') center/cover;">
```

#### 2. Real Testimonials
Replace placeholder testimonials with actual client reviews:
```html
<div class="testimonial-card">
  <span class="quote-mark">"</span>
  <div class="testimonial-content">
    "Actual client testimonial text here..."
  </div>
  <div class="testimonial-author">— Actual Client Name</div>
</div>
```

#### 3. Service Details
Update service descriptions and add specific project examples.

### Update Business Information
All business details are centralized in these locations:

#### Header/Logo
```html
<a href="#home" class="logo">ALIGN <span>INTERIORS</span></a>
```

#### Contact Section
```html
<a href="tel:+919766045538" class="direct-link">Call +91 97660 45538</a>
```

#### Footer
```html
<p class="footer-phone"><a href="tel:+919766045538">+91 97660 45538</a></p>
<p class="footer-address">
  Estonia Office No. 504-B,<br>
  Gulawani Maharaj Road,<br>
  opposite Mehendale Garage,<br>
  Erandwane, Pune,<br>
  Maharashtra 411004
</p>
```

#### Google Maps
Update the iframe `src` attribute if office location changes.

### Customize Colors
All colors are defined as CSS custom properties in the `:root` section:

```css
:root {
  --warm-ivory: #F7F4F0;      /* Primary background */
  --deep-espresso: #1A1816;   /* Primary text, dark surfaces */
  --stone: #E8E2DA;           /* Secondary background, card fills */
  --warm-taupe: #8C7E6E;      /* Secondary text, borders */
  --muted-brass: #B09968;     /* Accent color */
  --pale-taupe: #D4CEC4;      /* Dividers, subtle borders */
}
```

## Browser Compatibility
- Chrome 80+ ✅
- Firefox 75+ ✅  
- Safari 13+ ✅
- Edge 80+ ✅
- Mobile browsers ✅

## Performance
- **No external requests** (all assets inline)
- **CSS optimized** with custom properties
- **JS minified** within the file
- **Images** are CSS gradients (replace with optimized JPGs for production)
- **Fonts:** System fonts only (no webfont downloads)

## Deployment Options

### Option 1: Simple Hosting
Upload `align-interiors.html` to any web hosting service. It's a single file with no dependencies.

### Option 2: GitHub Pages
1. Create a GitHub repository
2. Upload `align-interiors.html` as `index.html`
3. Enable GitHub Pages in repository settings

### Option 3: Netlify/Vercel
Drag and drop the file to Netlify or Vercel for automatic deployment with CDN.

### Option 4: Traditional Web Host
Upload to your web server's public_html or www directory.

## Maintenance Notes

### Form Handling
The contact form currently shows a success message but doesn't actually send data. For production:

1. **Add a backend endpoint** (PHP, Node.js, etc.)
2. **Update form action**:
```html
<form action="https://your-backend.com/submit" method="POST">
```

### Analytics
Add Google Analytics or other tracking code before the closing `</body>` tag:
```html
<script>
  // Google Analytics code here
</script>
```

### SEO Improvements
- Add more specific meta tags for Open Graph
- Submit sitemap to Google Search Console  
- Add structured data (JSON-LD) for local business

## Support
The website is built to be maintainable by non-technical users:

1. **All content is editable** - Just open the HTML file in a text editor
2. **No build process** - Edit and save, then refresh browser
3. **No dependencies** - Everything works out of the box
4. **Responsive by default** - No need to test multiple files

## Credits
- **Design:** Premium interior design studio aesthetic
- **Development:** Single-file architecture for simplicity
- **Content:** Original copy written for Align Interiors brand voice
- **Images:** CSS gradient placeholders (replace with actual project photos)

---

**Align Interiors** - Thoughtful Spaces. Timeless Interiors.