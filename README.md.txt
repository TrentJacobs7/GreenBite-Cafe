GreenBite Café - Website Project
Project Overview
A modern, responsive website for GreenBite Café, a healthy eating café in Johannesburg.
Learning Outcomes Achieved
Created an external CSS stylesheet (`style.css`) and linked it to all pages.
Used appropriate selectors and CSS properties for styling.
Applied responsive design using media queries and relative units.
Used CSS Grid for layout structure.
Implemented hover effects and modern card design.
Tested website on multiple screen sizes using browser developer tools.
Implemented JavaScript form validation with live inline error messages.
Used `fetch()` for AJAX form submission without page reloads.
Built interactive UI components: lightbox gallery, category filter tabs.
Added lazy-loading to images for improved page speed.
Added `robots.txt` and `sitemap.xml` for basic SEO.
Features
Fully responsive design (Desktop, Tablet, Mobile)
Consistent navigation across all pages
Beautiful hero section with custom image
Menu with price guide, category filter tabs, and "Order Now" buttons
Lightbox image gallery on Menu page (click any dish to enlarge)
Special offers page with attractive cards
Professional About Us and Reviews sections
Contact page with validated AJAX form (sends email via FormSubmit)
Catering enquiry page with validated form and estimated cost calculator
Lazy-loaded images for faster page load
Files Included
`index.html`
`AboutUs.html`
`Menu.html`
`Deals.html`
`Contact.html`
`Reviews.html`
`enquiry.html`
`style.css`
`robots.txt`
`sitemap.xml`
Images in `Assets/` folder
Responsive Design
Uses relative units (`rem`, `%`)
Multiple breakpoints:
Desktop (>1024px)
Tablet (768px - 1024px)
Mobile (<768px)
Testing
Tested on Google Chrome Developer Tools for:
Desktop (1920px)
Tablet (iPad - 768px)
Mobile (iPhone SE - 375px)
---
Changelog
[Part 3] - Page Speed
Added `loading="lazy"` to all images in `Menu.html` and `Deals.html` so images only load as the user scrolls to them, reducing initial page load time.
[Part 3] - Added Catering Enquiry Page
Created `enquiry.html` with a catering/large order enquiry form
Added fields: full name, email, phone, event date, guest count, catering package, optional notes
Implemented HTML5 validation (required fields, email format, phone pattern, date/guest limits)
Implemented JavaScript validation with live inline error messages
Implemented AJAX form submission using `fetch()`
On successful submission, displays a calculated cost estimate and availability response
Added "Catering" link to navigation menu across all pages
Fixed `style.css` (had become corrupted with HTML/JS content accidentally pasted in; restored to valid CSS and merged in shared form styles)
[Part 3] - Upgraded Contact Form
Rebuilt `Contact.html` form with proper `<label>` elements and form-group structure
Implemented HTML5 validation (required fields, email type, minlength on name/message)
Implemented JavaScript validation with live inline error messages
Implemented real AJAX email submission via FormSubmit (`fetch()` to `formsubmit.co/ajax/`)
Form now compiles submitted data into an email and sends it to `info@greenbite.com`
Fixed inconsistent email address shown across the page (now `info@greenbite.com` everywhere)
[Part 3] - Added Lightbox Gallery to Menu Page
Implemented a lightbox for the menu image gallery in `Menu.html`
Clicking any dish image opens a larger view with name and description
Added prev/next navigation (buttons + arrow keys) to browse all dishes
Added close functionality via close button, outside click, and Escape key
Added "Catering" nav link to `Menu.html` (was missing)
Added supporting CSS for lightbox to `style.css`
[Part 3] - Added Category Filter Tabs to Menu
Added filter tab buttons (All, Smoothies, Salads, Sandwiches/Panini, Light Meals) to `Menu.html`
Tagged each menu card with a `data-category` attribute matching the price table categories
Implemented JavaScript click-to-filter functionality with active tab styling
Added fade-in animation when filtered results display
Fulfils the "dynamic content / filter" requirement alongside the interactive tabs element
Added supporting CSS for filter tabs to `style.css`
[Part 2] - Responsive Design & Styling
Improved responsive design with media queries
Added price guide table on Menu page
Enhanced card hover effects
Updated About Us and Reviews layout
Fixed navigation consistency
---
References
MDN Web Docs. (2024). The loading attribute — lazy loading images. Mozilla. https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#loading
MDN Web Docs. (2024). Fetch API. Mozilla. https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
MDN Web Docs. (2024). Client-side form validation. Mozilla. https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation
MDN Web Docs. (2024). CSS Grid Layout. Mozilla. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
MDN Web Docs. (2024). Using media queries. Mozilla. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
FormSubmit. (2024). FormSubmit — HTML form to email service. https://formsubmit.co
W3Schools. (2024). HTML Input Types. https://www.w3schools.com/html/html_form_input_types.asp
Google. (2024). Introduction to robots.txt. Google Search Central. https://developers.google.com/search/docs/crawling-indexing/robots/intro
Sitemaps.org. (2024). What are Sitemaps? https://www.sitemaps.org/protocol.html
---
Submitted by: Trent Jacobs  
Date: 2026/06/20