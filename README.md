# Karabo’s Clothing Store

## ✅ Responsive Testing (Different Devices / Screen Sizes)

This document includes evidence of how the website adapts across common viewport sizes.

### Screen size evidence
> **Note:** Replace the placeholder filenames below with your real screenshots after capturing them on each device/browser.

| Device / Viewport | Approx Width x Height | Page | Screenshot |
|---|---:|---|---|
| Desktop | 1440 x 900 | Home / Products | `screenshots/desktop-1440x900.png` |
| Laptop | 1024 x 768 | Home / Products | `screenshots/laptop-1024x768.png` |
| Tablet | 768 x 1024 | Products / Enquiry | `screenshots/tablet-768x1024.png` |
| Mobile (small) | 375 x 667 | Nav / Enquiry form | `screenshots/mobile-375x667.png` |
| Mobile (very small) | 320 x 568 | Products grid | `screenshots/mobile-320x568.png` |

### What we tested
- Navigation links remain usable on small screens.
- Product images scale inside cards and maintain aspect ratio (`object-fit: contain`).
- Product grid adapts using CSS Grid with `minmax()`.
- Enquiry form stays readable with `width: 100%` inputs.

### Breakpoints used
From `style.css`:
- `@media (max-width: 768px)`
- `@media (max-width: 480px)`

### Screenshot capture checklist
Capture screenshots for:
1. **Products page** on desktop + mobile.
2. **Enquiry page** on mobile (check input spacing and button alignment).
3. **Navbar** on mobile (ensure it doesn’t overflow).

---

## Project Overview
Karabo’s Clothing Store is a simple web-based retail platform designed to showcase and sell clothing items online. The website provides users with an easy and organized way to browse products, learn about the business, make enquiries, and get in touch with the store.

## Website Goals & Objectives
- Create a user-friendly online clothing store interface
- Display clothing products in a clear and structured format
- Allow users to submit enquiries easily
- Provide essential business information (About & Contact)
- Build a responsive and accessible HTML-based website

## Key Features & Functionality
- Home page introducing the store
- Products page displaying clothing items
- About Us page with business information
- Enquiry form for customer questions
- Contact page with communication details
- Easy navigation between all pages

## Project Structure
```
Karabo-s-Clothing-Store/
│
├── index.html
├── about.html
├── products.html
├── contact.html
├── enquiry.html
├── style.css
└── script.js
```

## Technologies Used
- HTML5
- CSS3
- JavaScript

## Version History (Changelog)
- v1.0 – Initial project setup with basic pages
- v1.1 – Added enquiry and contact functionality
- v1.2 – Improved layout and navigation structure
- v1.3 – Final review and bug fixes


