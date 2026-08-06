# Wellbeing Nutrition - CRO-Optimized Product Detail Page (PDP)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

A single-file, production-quality HTML Product Detail Page (PDP) built for **Wellbeing Nutrition's Pure Korean Marine Collagen Peptides**. This rebuild focuses heavily on **Conversion Rate Optimization (CRO)**, integrating specific design and UX improvements derived from a detailed audit of the original live page.

---

## 🎯 Overview

This project is a case study in applying data-driven CRO principles to a premium D2C ecommerce storefront. It addresses 12 critical UX flaws, reducing cognitive load, improving message matching, and surfacing key trust signals exactly where users need them most. 

The aesthetic is clean, clinical-premium, and minimal—utilizing a white background, teal/seafoam accents (matching the product packaging), high-contrast CTAs, and a sophisticated typography pairing (Playfair Display & Inter).

---

## 🛠️ Key CRO Implementations

1. **Above-the-Fold Optimization:** Price, star rating, variant selector, and the primary CTA are immediately visible without scrolling.
2. **Cognitive Load Reduction:** Cross-sell and "similar products" modules are repositioned below reviews and "Frequently Bought Together" sections to keep the user focused on the primary product.
3. **Contextual Social Proof:** Trust badges are placed adjacent to the CTA, and superscript anchor links guide users directly to clinical research.
4. **Pricing Clarity:** Implemented per-bottle pricing within the pack selector, alongside clear "Best Value" and "Most Popular" badges.
5. **Urgency Indicators:** Integrated a functional countdown timer for promotions (with an evergreen fallback state).
6. **Dietary Indicators:** Prominently surfaced the "Non-Veg" indicator (red dot) in the hero meta row, as marine collagen is fish-derived.
7. **Subscribe & Save Friction:** Added a seamless, functional toggle that instantly updates pricing to reflect a 20% discount.
8. **Persistent Conversion:** Added a JS-driven, scroll-triggered sticky "Add to Cart" bar that keeps the CTA accessible at all times.
9. **Enhanced Review Widget:** Rebuilt the review section with functional filters (rating + specific concerns like Skin/Hair/Joints).
10. **Paid Traffic Strategy:** Documented best practices (in code comments) for creating a dedicated landing page variant for cold traffic to improve message-matching.
11. **Strategic Bundling:** Added a "Frequently Bought Together" module (Collagen + Vitamin C) with a bundled discount to increase AOV.
12. **Micro-Trust Signals:** Added "Secure Checkout," "Est. Delivery," and "Easy Returns" micro-icons directly below the main buy box.

---

## 💻 Technical Details & Interactive Elements

- **Vanilla Stack:** Built entirely without external frameworks using pure HTML5, CSS3, and Vanilla JavaScript.
- **Responsive Design:** Mobile-first architecture with custom breakpoints (480px, 640px, 768px, 1024px) ensuring a flawless experience across all devices.
- **Accessibility (a11y):** Implemented ARIA roles, descriptive alt text for imagery, and keyboard-navigable elements.
- **Performance Optimized:** Uses inline SVG icons, lazy-loaded images, and `requestAnimationFrame` for buttery-smooth scroll event handling.

### Interactive Features (Vanilla JS)
- Dynamic pricing engine (updates based on pack selection and subscription status).
- Scroll-triggered sticky Add-To-Cart bar.
- Animated accordion for FAQs.
- Tabbed filtering system for customer reviews.
- Real-time countdown timer logic.
- Variant switching (Flavor selection).

---

## 🚀 Getting Started

Since this is a static frontend build, no build tools or package managers are required.

1. Clone the repository.
2. Open `index.html` directly in any modern web browser.
3. Interact with the page (select packs, toggle subscription, scroll to trigger the sticky bar) to see the JS logic in action.

---

## 📁 Directory Structure

```text
/
├── index.html        # The complete, single-file PDP (HTML/CSS/JS)
├── README.md         # Project documentation
└── images/           # Product and lifestyle assets
```

---

*Designed and developed as a comprehensive CRO rebuild and UX engineering case study.*
