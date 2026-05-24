---
name: frontend-design
description: Guidelines and technical specifications for creating premium, high-fidelity frontend applications—including static websites, webpages, dashboards, and chatbots—following the Obsidian-Emerald design system.
license: MIT
---

# Frontend Design Guidelines & Implementation Skill

This skill provides comprehensive instructions, constraints, and guidelines for AI agents to implement premium, visually stunning, and highly performant frontend interfaces across multiple application archetypes. It is calibrated to respect high-end editorial pacing, clean presentation formats, and strict compliance with the **Obsidian Slate-Blue & Subdued Emerald** design system.

---

## 1. Core Philosophy & Premium Aesthetic Pillars

When building frontend applications, agents must prioritize visual excellence and dynamic, premium designs. **Basic, generic, or plain-looking interfaces are unacceptable.**

### A. Strict Color Dialect
- **Primary Canvas Floor:** Obsidian Slate-Blue (`#0a0e17`) must be used as the absolute background for all layouts (dashboards, websites, chatbots, etc.).
- **Surface Elevation:** Use Surface Soft (`#111827`) for cards, container sections, text containers, and chat balloons.
- **Active Focus & High Impact Dialect:** Subdued Emerald Green (`#09815c`) serves as the active focus indicator (selected states, active metrics, button accents, navigation paths).
- **Hairline Boundaries:** Standard boundaries must use a sharp `1px` border of Slate Hairline (`#1f293d`). Never rely on fuzzy drop shadows for dark elements.

### B. High-End Editorial Typography
- **Primary Serif Font:** **Petrona Serif** (from Google Fonts) must be used for primary branding, page headers, case study highlights, hero headers, and high-impact editorial typography.
- **Support Sans Font:** Clean, modern Sans-serif (like *Inter* or *Outfit*) for numerical telemetry, body text, chatbot responses, and system labels to maintain optimal legibility.
- **Pacing & Spacing:** Use generous vertical padding and line-heights to create breathing room, echoing the pacing of premium digital publications.

### C. Dynamic Interactions & Micro-Animations
- **Hover Transitions:** All interactive elements (links, buttons, navigation items) must feature smooth transitions (e.g., `transition: all 0.3s ease`).
- **Telemetry & Status States:** Status indicators and badges must feel active. Use pulsing green indicators for active states and muted text for inactive ones.

---

## 2. Application Archetypes & Component Specifications

This design language is highly versatile and must be adapted systematically for the following formats:

### A. Static Websites & Landing Pages
- **Hero Sections:** Large, elegant headers rendered in *Petrona Serif*, surrounded by generous vertical padding, over the deep `#0a0e17` background.
- **Feature Cards (`feature-card-tabbed`):** Background set to Surface Soft (`#111827`), outlined by a thin `1px solid #1f293d` border.
- **Call-to-Action Pills:** Use standard canvas-backing buttons (`button-pricing-pill`) for secondary links, and solid emerald-backed pills for primary buttons.
- **Highlight Blocks (`sage-callout-card`):** Use thin, low-contrast sage green framing (`1px solid #86efac`) to draw attention to success stories or testimonials.

### B. Analytical & Reporting Dashboards
- **Grid Layouts:** Keep structural segments clean using exact `1px solid #1f293d` grid lines. No box shadows.
- **Data Visualizations / Delta Labels:** Display key values clearly. Use positive delta indicators (`+12.4%`) highlighted in subdued emerald to signify progress.
- **Active Selection states:** Active metric filters and navigation rail states should highlight their borders or backgrounds with `#09815c`.

### C. Conversational Interfaces & Chatbots
- **Chat Window Area:** Obsidian Slate-Blue (`#0a0e17`) base.
- **User Messages:** Right-aligned bubble container utilizing Surface Soft (`#111827`) and Slate Hairline (`#1f293d`) borders.
- **Chatbot Response Messages:** Left-aligned container using Surface Soft (`#111827`) with a 1px border highlighted in Subdued Emerald (`#09815c`) or Sage Muted (`#86efac`) to establish narrative contrast and trust.
- **Input Bar:** Crisp and modern with focus transitions scaling the border color cleanly from `#1f293d` to `#09815c`.

### D. Pricing & Tier Displays
- **Standard Option (`pricing-tier-card`):** Surface Soft (`#111827`) card, thin Slate border.
- **Featured Option (`pricing-tier-card-featured`):** Outlined with a high-contrast `1px solid #09815c` (luminous highlight) to immediately guide user decision-making.

---

## 3. Implementation Workflow

### Step 1: Initialize Foundations
1. **Fonts Setup:** Include Google Fonts links for `Petrona` and `Inter` in the `<head>` of the application.
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=Petrona:ital,wght@0,300..600;1,300..600&display=swap" rel="stylesheet">
   ```
2. **Design Tokens / CSS Variables:** Configure root variables in the main CSS file.
   ```css
   :root {
     --bg-canvas: #0a0e17;
     --bg-surface-soft: #111827;
     --border-hairline: #1f293d;
     --border-sage-muted: #86efac;
     --color-emerald-accent: #09815c;
     --font-serif: 'Petrona', Georgia, serif;
     --font-sans: 'Inter', sans-serif;
   }
   ```

### Step 2: Build Layouts & Grid Architecture
- Implement layouts using modern CSS Flexbox and Grid.
- Use explicit pixel borders (`1px solid var(--border-hairline)`) instead of heavy shadows or complex box-shadows.

### Step 3: Polish and Validate
- Verify the UI across device screen widths to ensure absolute responsiveness.
- Optimize interactions with smooth, responsive CSS hover effects.

---

## 4. Design Compliance Checklist

### Do:
- [x] **DO** maintain the Obsidian Slate-Blue (`#0a0e17`) canvas as the absolute background floor across all digital interfaces (landing pages, dashboards, chatbots).
- [x] **DO** use Subdued Emerald Green (`#09815c`) for navigation, active focus paths, button states, and critical highlighted states.
- [x] **DO** pair the elegant Petrona serif layout structures with generous vertical spacing to respect high-end editorial pacing.
- [x] **DO** outline cards and message blocks with a sharp `1px` boundary border (`#1f293d`).

### Don't:
- [ ] **DON'T** introduce warm copper, terracotta, active orange, or glowing yellow highlight layers.
- [ ] **DON'T** rely on blurred drop shadows for dark elements. Keep layouts clean with sharp hairline borders.
- [ ] **DON'T** use bright neon greens. Keep all emerald highlights tuned precisely to the muted depth of `#09815c`.
- [ ] **DON'T** use unstyled browser elements or native colors. Everything should look bespoke and high-fidelity.
