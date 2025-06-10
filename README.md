# BLATA Printing & Advertising Website

![BLATA Printing Header](images/social-preview.jpg)

## Overview
A responsive, multilingual website for BLATA Printing & Advertising, a premier printing service provider in Mekelle, Ethiopia. The site showcases services, allows online orders, and provides company information in English, Tigrinya, and Amharic.

## Key Features
- 🌐 **Multilingual Support** (English, Tigrinya, Amharic)
- 🖥️ **Fully Responsive Design** (Mobile, Tablet, Desktop)
- 🎨 **Dark/Light Mode Toggle**
- 📝 **Online Order Form** with file uploads
- 📱 **Floating WhatsApp CTA**
- 📬 **Newsletter Subscription**
- 🏆 **Customer Testimonials**
- 🗺️ **Interactive Location Map**

## Technical Specifications
| Category        | Details                                                                 |
|-----------------|-------------------------------------------------------------------------|
| Frontend        | HTML5, CSS3, JavaScript (Vanilla)                                      |
| CSS Features    | CSS Variables, Flexbox, Grid, Animations, Media Queries                |
| Accessibility   | WCAG 2.1 AA compliant (ARIA labels, keyboard navigation)               |
| Performance     | 95+ Lighthouse Score (Optimized images, lazy loading)                  |
| Form Handling   | Formspree backend integration                                          |
| Dependencies    | Font Awesome, Google Fonts (Poppins)                                   |

## Installation
No installation required - static website ready for deployment:

1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/blata-printing.git
Deploy to any static hosting:

Netlify

Vercel

GitHub Pages

Traditional web hosting

File Structure
text
blata-printing/
├── index.html          # Main website file
├── images/             # Optimized WebP images
│   ├── banners/
│   ├── products/
│   └── social-preview.jpg
├── styles/             # CSS files (optional)
│   ├── main.css
│   └── dark-mode.css
└── README.md
Customization Guide
Update Business Info

Edit contact details in the <footer> and contact section

Update Google Maps iframe with your exact location

Change Colors
Modify CSS variables in :root:

css
:root {
  --primary: #004080;       /* Main brand color */
  --accent1: #e74c3c;       /* Secondary color */
  --accent2: #3498db;       /* Action color */
}
Update Translations
Edit the translations object in JavaScript:

javascript
const translations = {
  en: {
    "services": "Services",
    "order": "Order Now"
  },
  ti: {
    "services": "ግልጋሎት",
    "order": "አሁን ይዘዙ"
  }
};
Form Configuration
Replace the Formspree endpoint in the order form:

html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
Recommended Image Specs
Usage	Format	Size	Aspect Ratio
Service Samples	WebP	800x600px	4:3
Product Showcase	WebP	1200x900px	4:3
Team Photos	WebP	600x600px	1:1
License
MIT License - Free for personal and commercial use.

Support
For technical issues, contact:
teklush7mit@gmail.com
