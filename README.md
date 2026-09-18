Brew & Bean Coffee Co. — Website

A responsive five-page website for a fictional artisan coffee shop based in Cape Town.

Student:PHENYO LAKA
Student Number:ST10469904
Subject:Web Development (Introduction)
Module Code:WEDE5020POE

contents

index.html 
about.html 
services.html 
enquiry.html 
contact.html 
style.css 
README.md
images/Site images
screenshots
references

Design

Colour scheme:
Coffee-themed palette using CSS named colours — `saddlebrown`, `peru`, `beige`, `white`, `black` — stored as CSS variables in `:root`.
Typography:** `Georgia` (serif) for headings, `Arial` (sans-serif) for body text.
Layout:** Centered content column (`max-width: 900px`) with soft shadows on section cards.

Responsive Design

 Breakpoint | Target | Changes 
 `max-width: 768px`  Tablet | Smaller headings, tighter padding 
 `max-width: 480px`  Mobile | Stacked navigation, single-column layout, smaller font 
Images use `srcset` and `sizes` attributes, plus the `<picture>` element on the homepage hero.

Changelog — Part 2

CSS Styling
Created external `style.css` and linked it to all 5 HTML pages.
Added a CSS reset (`* { margin: 0; padding: 0; box-sizing: border-box; }`).
Defined the colour scheme as CSS variables in `:root`.
Applied typography: `font-family`, `font-size`, `line-height`, `letter-spacing`.
Applied visual styles: background colours, borders, `border-radius`, `box-shadow`.
Added interactive states: `:hover`, `:focus`, `:active` on all links.

Layout
Styled header with dark brown background and centered content.
Styled navigation as a horizontal inline menu.
Styled `<main>` as a centered column with max-width.
Styled sections as white cards with padding and shadows.
Styled footer with dark background and centered text.

Responsive Design
Added `@media (max-width: 768px)` for tablet.
Added `@media (max-width: 480px)` for mobile.
Used relative units (`rem`, `%`) throughout.

Responsive Images
Added `srcset` and `sizes` attributes to all `<img>` tags.
Used the `<picture>` element on the homepage hero image.
Added descriptive `alt` text to all images.

Fixes
Removed invalid `height="auto"` attributes from `<img>` tags.
Corrected `call-us.jpg` → `call-us.jpeg`.
Corrected Windows backslash `\` to forward slash `/` in image paths.
Renamed `coffee community.jpeg` to `coffee-community.jpeg` (removed space).

Screenshots

Laptop
![image alt](https://github.com/phenyolaka30-source/My-Website/blob/b227bb2d2c2fe79be67ef0ff1cd8b8dc059ba2aa/images/laptop.png)
mobile
![image alt](https://github.com/phenyolaka30-source/My-Website/blob/d6316953de1072ead6934ba5e303050904a4fe2b/images/mobile.png)
tablet
![image alt](

References

MDN Web Docs — CSS: https://developer.mozilla.org/en-US/docs/Web/CSS
MDN Web Docs — Responsive Images: https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images
MDN Web Docs — CSS Variables: https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties
W3Schools — CSS Media Queries: https://www.w3schools.com/css/css3_mediaqueries.asp
W3Schools — CSS Colour Names: https://www.w3schools.com/cssref/css_colors.asp
