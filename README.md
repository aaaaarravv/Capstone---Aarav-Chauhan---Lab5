# Capstone---Aarav-Chauhan---Lab5

# Fashionista — E-commerce Store UI (HTML5 & CSS3)

## Theme
E-commerce Store UI: Product listing, filter sidebar, hero/banner with CTA, best sellers, testimonials, and newsletter subscribe form.

## Sections implemented
- **Header & Navigation:** Brand, primary links, utility icons, “Skip to main content”.
- **Hero/Banner:** Headline, tagline, CTA, flash sale callout with countdown.
- **Filters Sidebar:** Category, price, color (visual-only; semantic form elements with labels).
- **Product Grid:** 4 products with images, titles, prices, add-to-cart buttons.
- **Best Sellers:** Highlighted SKUs.
- **Testimonials:** 3 customer quotes with avatars.
- **Newsletter Form:** Accessible label and required email field.
- **Footer:** Account/help/policies/social links + copyright.

## Layout & responsiveness
- **Techniques:** Flexbox (header/footer alignment), CSS Grid (product/testimonial/footers), semantic HTML.
- **Variables:** Colors, spacing, radii, shadows via `:root`.
- **Breakpoints:** Desktop ≥1024px (4-col grid), Tablet ~768px (2–3 cols, stacked header), Mobile ≤560px (single-column).
- **Units:** rem/% for spacing and sizing.

## Visual polish
- **Typography:** Inter + Playfair Display (Google Fonts).
- **Hover/Transitions:** Cards elevate, links and buttons transition.
- **Animation:** Hero headline fade+slide keyframe.
- **Contrast:** Dark text on light surfaces; clear focus styles.

## Accessibility
- **Alt text:** All images meaningful.
- **Labels:** Forms with associated labels.
- **ARIA:** Landmark roles via semantics, nav `aria-label`, live region for flash sale text.

## How to run
- **Local:** Open `index.html` in your browser.
- **Images:** Place assets in `images/` with the filenames used in HTML.
- **Optional:** Host via GitHub Pages (push repo and enable Pages).

## Notes
- Visual filters are non-functional per assignment (no JS).
- Optimize images before submission (compress to ~200–400KB where possible).
