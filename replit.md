# BeeWild Education Website

## Overview

BeeWild is a static website for an educational organization focused on nature-based learning and English language education. The site showcases various educational programs including EcoExplorers, WildFit, Conversational English, and Science in English. It's built using the "Forty" HTML5 template and serves as a marketing/informational website for the organization.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static HTML Website**: Pure HTML/CSS/JS with no build system or framework
- **Template Base**: Built on the "Forty" theme by HTML5 UP (html5up.net)
- **CSS Framework**: Custom CSS with Font Awesome icons for iconography
- **JavaScript Libraries**:
  - jQuery 3.6.0 for DOM manipulation
  - Skel.js for responsive breakpoint handling
  - jQuery Scrollex/Scrolly for scroll-based effects
  - Custom util.js for navigation panel functionality

### Page Structure
- `index.html` - Homepage
- `about-me.html` - About BeeWild page
- `elements.html` - Projects page
- `generic.html` - Contact page
- `landing.html` - Blog page
- Program-specific pages: `Eco-Explorers.html`, `wildfit.html`, `conversational-english.html`, `science-in-english.html`, `educationconection.html`
- Legacy blog posts in `/2016/08/` directory (from original template)

### Design Patterns
- **Responsive Design**: Mobile-first approach with breakpoints for xlarge, large, medium, small, xsmall, xxsmall screens
- **Parallax Scrolling**: Background parallax effects on banner sections
- **Consistent Navigation**: Shared header and hamburger menu structure across all pages

### Browser Compatibility
- IE8/IE9 fallback stylesheets and HTML5 shiv for older browser support
- Respond.js polyfill for media queries in legacy browsers

## External Dependencies

### CDN/External Resources
- **Google Fonts**: Source Sans Pro (300, 300italic, 600, 600italic weights)

### Local Assets
- **Font Awesome 4.6.3**: Icon library (loaded locally from `/assets/fonts/`)
- **jQuery 3.6.0**: Core JavaScript library
- **Skel.js v3.0.1**: Responsive framework

### No Backend Dependencies
This is a purely static site with no:
- Database connections
- Server-side processing
- API integrations
- Authentication systems
- Form processing backends (forms exist but submission handling not implemented)