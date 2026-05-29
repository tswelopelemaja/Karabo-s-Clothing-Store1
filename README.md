Karabo’s Clothing Store

Responsive Testing for different devices and screen sizes

Evidence of how the website adapts across common viewport sizes.

Screen size evidence


 Device / Viewport  Approx Width x Height  Page Screenshot 
 

| Desktop | 1440 x 900 | Home / Products | `screenshots/desktop-1440x900.png` |
| Laptop | 1024 x 768 | Home / Products | `screenshots/laptop-1024x768.png` |
| Tablet | 768 x 1024 | Products / Enquiry | `screenshots/tablet-768x1024.png` |
| Mobile (small) | 375 x 667 | Nav / Enquiry form | `screenshots/mobile-375x667.png` |
| Mobile (very small) | 320 x 568 | Products grid  `screenshots/mobile-320x568.png` 

 What I tested
 
- Navigation links remain usable on small screens.
- Product images scale inside cards and maintain aspect ratio (`object-fit: contain`).
- Product grid adapts using CSS Grid with `minmax()`.
- Enquiry form stays readable with `width: 100%` inputs.

 Breakpoints that I used
 
From `style.css`:
- `@media (max-width: 768px)`
- `@media (max-width: 480px)`

Screenshot capture checklist

Capture screenshots for:
1. Products page on desktop + mobile.
2. Enquiry page on mobile (check input spacing and button alignment).
3. Navbar on mobile (ensure it doesn’t overflow).



Project Overview

Karabo’s Clothing Store is a simple web-based retail platform designed to showcase and sell clothing items online. The website provides users with an easy and organized way to browse products, learn about the business, make enquiries, and get in touch with the store. The products that are offered are jeans,jackets,shoes,suits for men. For women dresses and skirts are also available, more options are available on the website. The enquiries are received by the team and feedback will be sent through a call or an email. 

 Website Goals & Objectives
 
- Create a user friendly online clothing store.
- Display clothing products in a clear and structured format.
- Allow users to submit enquiries easily.
- Provide communication details such as About and Contact pages.
- Build a responsive and accessible HTML-based website.
  
Functionality and key features 

- Home page is responsible for the introduction of the store.
- Products page displays clothing items for men,women and kids.
- About Us page has the business information.
- Enquiry form for customer questions and enquiries regarding the clothing options.
- Contact page shows the communication details.
- Easy navigation is ensured through all pages.

Project Structure
Karabo-s-Clothing-Store

index.html
about.html
products.html
contact.html
enquiry.html
style.css



 Technologies that were used
 
- HTML5
- CSS3
  

 Changelog
 
Initial project setup with basic pages

Added enquiry and contact functionality

Improved layout and navigation structure

Final review and bug fixes

Reference List (Harvard style)

W3Schools (n.d.) *W3Schools Online Web Tutorials*. Available at: https://www.w3schools.com/ (Accessed: 29 May 2026).





