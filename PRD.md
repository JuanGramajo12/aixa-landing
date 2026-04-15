# This updated Product Requirements Document (PRD) incorporates a **Multi-Device Responsive Strategy**. The goal is to translate the high-end "Framer" and "Landbook" aesthetic into a fluid experience that feels native whether viewed on a 27-inch monitor or a 6-inch smartphone.

---

## Updated PRD: Aixa Group Landing Page (Responsive Edition)

### 1. Responsive Design Framework & Breakpoints

To ensure a "pixel-perfect" feel, we will use a fluid grid system with the following defined breakpoints:

# * **Mobile (Portrait):** 320px – 480px (Single column, optimized for thumb-reach).
* **Tablet (Portrait):** 481px – 768px (Two-column grids, simplified navigation).
* **Laptop/Desktop:** 769px – 1440px (Standard multi-column layout, full hover effects).
* **Large Desktop (4K/Ultrawide):** 1441px+ (Max-width container of 1200px to prevent "line-stretching").

---

### 2. Section-by-Section Responsive Adaptations

#### **Section 1: Hero / Header**

* **Desktop/Laptop:** Split-screen layout. Machine imagery on the right, bold value proposition and CTA on the left.
* **Mobile/Tablet:** **Stacked layout.** The headline moves to the top, followed by a condensed version of the machine image, then the CTA.
* **Header Nav:** * *Desktop:* Full horizontal menu.
  * *Mobile/Tablet:* **Sticky Hamburger Menu** that opens into a full-screen blurred overlay (Framer-style).
* **Action Bar:** On mobile, the WhatsApp/Contact bar becomes a **fixed footer button** for instant access without scrolling back up.

#### **Section 2: The Problem (Grid to List)**

* **Desktop:** 3-column horizontal grid. High-quality icons above short, punchy paragraphs.
* **Mobile:** **Vertical stack with "Scroll Reveal."** Each problem card takes up 80% of the viewport height as the user scrolls, creating a storytelling effect similar to the "Landbook" motivational style.
* **Typography:** Headline font sizes scale dynamically (e.g., 64px on Desktop down to 32px on Mobile) to ensure no awkward line breaks.

#### **Section 3: The Machine (Interactive Elements)**

* **Desktop:** Interactive "hotspots" on the machine photo. Hovering over the screen shows the software; hovering over the oven shows baking specs.
* **Mobile/Tablet:** **Touch-Carousel.** Since hover doesn't exist on mobile, users swipe through a series of "Detail Cards" (e.g., Card 1: The Oven, Card 2: The Software, Card 3: The Footprint).
* **Software Preview:** On mobile, use a "Mobile App View" mockup of the analytics dashboard rather than the desktop version to emphasize remote management.

#### **Section 4: The Menu (The "Fithu" Aesthetic)**

* **Desktop:** Large circular "plates" arranged in a 3x2 or 4x2 grid.
* **Mobile:** **Horizontal "Snap" Slider.** Users swipe left and right to see the different pizzas. The "Add to Interest" or "Details" buttons are enlarged for "fat-finger" friendliness (minimum 44px touch target).
* **Visuals:** Pizzas should remain high-resolution, but use WebP format to ensure lightning-fast loading on mobile data speeds.

---

### 3. Technical & Functional Requirements (Responsive Focus)

| Feature                 | Desktop/Laptop Requirement                         | Mobile/Tablet Requirement                                          |
| :---------------------- | :------------------------------------------------- | :----------------------------------------------------------------- |
| **Navigation**    | Standard Top-Bar (Transparent to Solid on scroll). | Sticky Header with Hamburger + Fixed CTA Footer.                   |
| **Hover Effects** | Scale-up and Glow effects on buttons/cards.        | **REMOVED.** Replaced with active-state color shifts on tap. |
| **Images**        | Retina-ready 2x assets.                            | Lazy-loaded, compressed mobile-specific crops.                     |
| **Contact Form**  | Side-by-side fields (Name/Email).                  | Full-width single-column fields for easier typing.                 |
| **Animations**    | Parallax backgrounds and complex entrance moves.   | Simplified "Fade-in-up" to preserve battery and CPU.               |

---

### 4. Cross-Device "Motivational" Messaging

To maintain the **Landbook** feel across devices, we will use "Utility Messaging":

* **Desktop:** "Scale your business to every corner of the city."
* **Mobile (Short & Punchy):** "Passive income, served hot."

### 5. Quality Assurance (The "Beauty" Check)

* **Zero Horizontal Scroll:** The page must never "wiggle" left or right on mobile.
* **Font Legibility:** Minimum body font of 16px on mobile to prevent zooming.
* **Safe Areas:** Ensure no buttons are cut off by the iPhone "Notch" or Android navigation bars.

This iteration ensures that the Aixa Group brand feels just as premium and "tech-forward" on a smartphone in a meeting as it does on a large office monitor. Ready to move to the wireframing stage?
