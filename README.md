# Let It Shine Creative Academy (LISCA) 🌟
> **Hope, Liberation & Progress**

Welcome to the official repository for the **LISCA landing page**—a modern, responsive, and premium web application designed to connect LISCA with sponsors, volunteers, donors, and the local community. LISCA is a non-profit educational initiative of **Let It Shine Academy (LISA)**, providing 100% free education, vocational training, and mentorship to children in underserved communities.

---

## 🎨 Design & Brand Identity

This website is built with a premium, tech-education aesthetic designed to inspire hope, credibility, and donor action. It combines modern layout dynamics with LISCA's core visual assets.

### Color System & Visual Identity

The brand colors are configured as CSS variables in [styles.css](styles.css) to ensure visual coherence across the page.

*   **Primary Brand Navy** (`#001F3F`): Used for primary dark backgrounds, footers, headers, and section title typography.
*   **Vibrant Sun Yellow** (`#FFC700`): The brand's signature accent color, used for high-visibility buttons, highlighted text, and badges.
*   **Accent Gold** (`#D97706`): Optimized for Web Content Accessibility Guidelines (WCAG) contrast compliance when used on white backgrounds.
*   **Dark Slate** (`#0F172A`): Softer body text black that reduces visual strain.
*   **Warm Off-White** (`#F8F9FA`): Used for secondary light sections to create layout rhythm.

### Visual Design Patterns
*   **Refined Glassmorphism**: Translucent frosted panels (`backdrop-filter: blur(12px)`) over dark containers (Hero and Stats counters) paired with clean outline panels on light containers.
*   **Fluid Typography**: Leveraging Google Fonts (`Outfit` for headings and `Inter` for body copy) with clamp-based fluid sizing.
*   **Interactive Shadows**: Micro-animations and custom transitions (`cubic-bezier(0.4, 0, 0.2, 1)`) on card hovers and form controls.

---

## 🚀 Key Features

*   **Sticky Translucent Navigation**: A header bar that remains fixed at the top of the viewport with a blur filter for background transparency.
*   **Auto-Closing Mobile Drawer**: Clever mobile navigation layout using a CSS toggle checkbox, enhanced with vanilla JavaScript to automatically slide the drawer shut when an anchor link is selected.
*   **Founder Spotlight Quote Card**: High-impact messaging section featuring a quote from Dammy Feyide.
*   **Programs Grid**: 6 distinct, hover-animated program cards detailing LISCA's academic support, web development, data analysis, shoemaking, agricultural science, and creative arts tracks.
*   **Impact Timeline**: A responsive layout tracing student success phases, community involvement, and leadership pathways.
*   **Interactive Donation Form**: Structured online sponsorship options ($20, $50, $100 tiers) with form input styling and visual response triggers.
*   **Responsive Contact Form**: Built-in native HTML5 validation constraints (length, type, required inputs) with clear visual success/invalid color states.
*   **Integrated Google Map**: A responsive iframe placeholder mapping the Alimosho, Lagos neighborhood location.

---

## ♿ Accessibility & SEO Best Practices

The LISCA landing page is designed to comply with modern web standards and **WCAG 2.2** accessibility markers:

1.  **Vibrant High Contrast**: Refined color variables guarantee that all text elements satisfy contrast ratio standards (4.5:1 for normal text).
2.  **Keyboard Focus Rings**: Custom `:focus-visible` indicators overlay a bright yellow focus ring on active controls, allowing keyboard-only and screen reader navigation.
3.  **Touch Target Optimization**: Interactive items (navigation links, buttons, social links) feature a minimum size of `44px × 44px` to ensure accurate touch inputs on mobile screens.
4.  **SEO & Open Graph Headers**: Full meta tags, descriptions, canonical links, and Open Graph card data are configured in the `<head>` to support search indexing and clean social media previews.
5.  **Layout Shift Prevention**: Explicit image dimensions and lazy loading (`loading="lazy"`) are applied to images to eliminate Cumulative Layout Shift (CLS).

---

## 📂 Project Structure

```bash
LISCA/
├── index.html        # Main HTML5 landing page file
├── styles.css        # Core design system stylesheet (CSS Variables, Flexbox, Grid)
├── images/           # Local visual assets directory
│   ├── founder.jpeg  # Profile portrait of founder Dammy Feyide
│   └── hero_bg.png   # Hero background image
└── README.md         # Project documentation (this file)
```

---

## 🛠️ Development & Local Run

As a lightweight HTML5/CSS3/JS project, this landing page runs without any compilation step, node modules, or build configurations.

### Running the Project
1.  Clone this directory to your computer.
2.  Ensure your images folder (`images/`) contains the necessary asset placeholders (`founder.jpeg` and `hero_bg.png`).
3.  Double-click `index.html` to open the page directly in your web browser.
4.  *(Recommended)* For developers, serve the directory using a lightweight server, such as the VS Code **Live Server** extension, to support hot-reloading.
