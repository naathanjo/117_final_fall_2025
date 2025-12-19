# IS117 Final Project: Creative Tech Portfolio Hub

**Student:** Jonathan Rojas  
**Course:** IS117  
**Live Site:** https://naathanjo.github.io/117_final_fall_2025/

---

## 📌 Project Overview

A comprehensive web development project showcasing three distinct sites built with responsive design principles, advanced CSS Grid systems, and semantic HTML5 architecture.

---

## 🛠️ Included Sites

### 1. **Personal Professional Portfolio**

**Archetype:** The Creator

**Purpose:** Present myself as a Creative Tech Engineer through interactive UX and professional presentation.

**Key Features:**
- Multi-page navigation system
- Semantic HTML5 structure
- Interactive components and micro-interactions
- Professional booking/consultation system

**Technologies:**
- HTML5 (semantic tags)
- CSS3 (Grid, Flexbox, animations)
- Vanilla JavaScript
- Responsive design (mobile-first)

---

### 2. **Design History: Humanist Modernism**

**Style:** Humanist Modernism

**Purpose:** Museum-quality presentation exploring the intersection of rational geometry and human-centered design principles.

**Key Features:**
- Asymmetrical 12-column CSS Grid layout
- High-legibility typographic systems
- Warm color palette (#f9f7f2, #2a2a2a, #d97706)
- Humanist sans-serif typography (Open Sans, Segoe UI)
- Gallery section with 3D renders
- Intersection Observer animations

**Technologies:**
- HTML5 semantic structure
- CSS3 Grid (12-column system)
- Fluid typography with `clamp()`
- JavaScript (Intersection Observer API)

**Color Palette:**
- Background: `#f9f7f2` (Warm off-white)
- Text: `#2a2a2a` (Deep charcoal)
- Accent: `#d97706` (Muted clay orange)

---

### 3. **Client Site: TrailMapper**

**Client:** Erick Rosas (Adventure Photographer & Trekker)

**Purpose:** Conversion-optimized landing page for a trail safety and navigation app.

**Key Features:**
- Responsive hamburger navigation menu
- Structured sales funnel (Hero → Features → Social Proof → CTA)
- Mobile-first responsive design
- Feature highlight cards (Offline Maps, AI Safety Alerts, Location Sharing)
- Testimonial section with social proof
- Email capture form with CTA
- Inclusive language for all adventurers

**Technologies:**
- HTML5 form elements with validation
- CSS3 (12-column Grid, Flexbox)
- Vanilla JavaScript (menu toggle, smooth scroll)
- ARIA accessibility labels
- Mobile hamburger menu with animation

**Color Palette:**
- Primary: `#2d5a27` (Forest Green)
- Secondary: `#333333` (Earthy Charcoal)
- Accent: `#ff6b35` (Safety Orange)
- Background: `#ffffff` (Clean white)

---

## 🔧 Technical Requirements Met

### HTML5 & Semantics
- ✅ Proper use of `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`
- ✅ ARIA labels for accessibility (`aria-label`, `aria-expanded`)
- ✅ Skip-to-content links on all pages
- ✅ Semantic form elements with validation

### Responsive Design
- ✅ Mobile-first approach
- ✅ Fluid typography using `clamp()`
- ✅ Flexible grid layouts
- ✅ Breakpoints: 1024px, 768px, 480px
- ✅ Touch-friendly interactive elements

### CSS Architecture
- ✅ Global CSS variables for consistency
- ✅ 12-column CSS Grid system
- ✅ Flexbox for component layouts
- ✅ CSS animations and transitions
- ✅ Rounded corners and shadows for depth
- ✅ Consistent spacing scale (xs, sm, md, lg, xl, xxl)

### JavaScript Functionality
- ✅ Mobile hamburger menu toggle
- ✅ Smooth scroll behavior for anchor links
- ✅ Intersection Observer API for animations
- ✅ Event delegation and cleanup
- ✅ ARIA state management (`aria-expanded`)

### Performance & Optimization
- ✅ Global stylesheet for shared variables
- ✅ Optimized image handling with alt text
- ✅ Preconnect and DNS prefetch hints
- ✅ Accessible color contrast ratios
- ✅ Lean JavaScript (no frameworks)

---

## 📁 Project Structure

```
117_final_fall_2025/
├── global.css                          # Shared variables and global styles
├── index.html                          # Portfolio hub landing page
├── docs/
│   ├── portfolio/
│   │   ├── index.html                 # Portfolio projects showcase
│   │   └── css/
│   │       └── portfolio-styles.css   # Portfolio-specific styles
│   ├── design_style/
│   │   ├── index.html                 # Humanist Modernism design study
│   │   ├── css/
│   │   │   └── humanist-styles.css   # Design study styles
│   │   └── images/                    # 3D renders and assets
│   └── client_site/
│       ├── index.html                 # TrailMapper landing page
│       ├── css/
│       │   └── client-styles.css     # TrailMapper styles
│       └── images/                    # Product and testimonial images
└── README.md                          # This file
```

---

## 🎨 Design Systems

### Color Variables
All sites use a consistent CSS variable structure:

```css
--color-primary:      /* Main brand color */
--color-secondary:    /* Complementary color */
--color-accent:       /* Call-to-action color */
--color-text:         /* Primary text */
--color-text-light:   /* Secondary text */
--color-bg:           /* Background */
--color-bg-alt:       /* Alternate background */
```

### Typography Scale
Fluid fonts that scale responsively:

```css
--font-size-h1:   clamp(2rem, 5vw, 3.5rem)
--font-size-h2:   clamp(1.75rem, 4vw, 2.5rem)
--font-size-h3:   clamp(1.25rem, 3vw, 1.4rem)
--font-size-body: clamp(0.95rem, 2vw, 1.1rem)
```

### Spacing Scale
Consistent spacing hierarchy:

```css
--spacing-xs:   0.5rem
--spacing-sm:   1rem
--spacing-md:   1.5rem
--spacing-lg:   2rem
--spacing-xl:   3rem
--spacing-xxl:  4rem
```

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd 117_final_fall_2025
   ```

2. **Open in browser:**
   - Main portfolio hub: `index.html`
   - Design study: `docs/design_style/index.html`
   - Client site: `docs/client_site/index.html`

3. **No build tools required** – all files are static HTML, CSS, and vanilla JavaScript.

---

## 📱 Responsive Breakpoints

| Device | Breakpoint | Layout |
|--------|-----------|--------|
| Mobile | < 480px | Single column, hamburger menu |
| Tablet | 480px – 768px | 2-column, mobile navigation |
| Laptop | 768px – 1024px | 3-4 column grid |
| Desktop | > 1024px | Full 12-column grid |

---

## ♿ Accessibility Features

- ✅ ARIA labels on interactive elements
- ✅ Semantic HTML structure
- ✅ Skip-to-content navigation links
- ✅ Keyboard-navigable menus
- ✅ High contrast color ratios (WCAG AA compliant)
- ✅ Alt text on all images
- ✅ Form validation and error messaging
- ✅ Focus states on all interactive elements

---

## 📝 Notes

- All pages are fully responsive and tested across major browsers
- JavaScript is vanilla (no frameworks or dependencies)
- Performance optimized with minimal external resources
- Images should be optimized before deployment (use WebP with fallbacks)

---

**Portfolio Hub:** https://github.com/naathanjo/117_final_fall_2025 
**Design Study:** Humanist Modernism exploration  
**Client Project:** TrailMapper – Trail Safety App Landing Page

*Last Updated: December 2025*