# Obsidian Slate-Blue & Emerald Green Design System Profile

A premium, cohesive visual design system engineered for high-fidelity digital interfaces. This design language provides a dark-mode foundation with low-glare, high-contrast typography, and strict, sharp boundaries. It is designed to scale across diverse application archetypes, including static websites, modern landing pages, administrative dashboards, chatbots, and interactive documentation.

---

## Design System Foundations

- **Design System Profile:** Airtable-design-analysis-dark-emerald-petrona
- **Canvas Background Floor:** Obsidian Slate-Blue (`#0a0e17`) — the absolute background color for all interface types.
- **Active Focus Accent:** Subdued Emerald Green (`#09815c`) — the primary accent color for selected states, interactive cues, high-impact borders, and primary calls-to-action.
- **Muted Sage Highlight:** Sage Muted (`#86efac`) — used for secondary highlights, subtle callouts, and narrative structures.
- **Borders & Outlines:** 1px Slate Hairline (`#1f293d`) — used for strict grid lines, content framing, and structural separation.
- **Typography Baseline:** 
  - **Brand & Headings:** Petrona Serif (for headlines, hero section typography, and premium editorial pacing).
  - **Body, UI, & Data:** Inter or Outfit Sans-Serif (for high-legibility interface controls, text blocks, numeric readouts, and message logs).

---

## 1. Global Navigation & Connectivity Telemetry

### Navigation Elements (Rail, Sidebar, or Header)
- **Active / Selected State:** Highlighted with Subdued Emerald Green (`#09815c`) text/accent border.
- **Inactive / Hover State:** Standard Slate-Blue canvas background, transitioning to a light grey-blue text focus.
- **Interactive Transitions:** Generous horizontal/vertical padding with smooth hover transitions (`transition: all 0.2s ease`).

### System Telemetry & Status
- **Connected / Active Badge:** Low-contrast background with text in `#09815c` and a subtle pulse animation.
- **Telemetry Node Details:** Small monospace fonts for technical data such as session IDs, status strings, or environment tags.

---

## 2. Structural Content & Card Layouts

All cards and structural items avoid blurred dropshadows, relying instead on clean surface elevations and crisp hairline borders.

### Standard Layout Containers (`feature-card-tabbed` / `pricing-tier-card`)
- **Background Specification:** Surface Soft (`#111827`)
- **Boundary Outline:** 1px Slate Hairline (`#1f293d`)
- **Use Case:** Metric showcases, static page features, text content blocks, and regular subscription tier descriptions.

### Narrative & Notice Callouts (`sage-callout-card`)
- **Background Specification:** Surface Soft (`#111827`)
- **Boundary Outline:** 1px Sage Muted (`#86efac`)
- **Use Case:** Editorial highlight boxes, key takeaways, announcements, or documentation notifications.

### Premium / Featured High-Impact Cards (`pricing-tier-card-featured`)
- **Background Specification:** Surface Dark Elevated (`#111827` or solid `#0f1422`)
- **Boundary Outline:** 1px Emerald Accent (`#09815c`) for a luminous structural highlight.
- **Use Case:** Highlighted pricing options, high-converting product features, or featured case studies.

---

## 3. Form Controls & Interactive Call-to-Actions

### Premium Buttons (`button-pricing-pill`)
- **Standard Button Pattern:** Canvas backing (transparent or dark background) outlined in 1px Slate Hairline (`#1f293d`) with smooth color-shifting hover effects.
- **High-Contrast / CTA Button Pattern:** Solid Subdued Emerald Green (`#09815c`) background with clean, high-contrast dark text, utilizing a pill shape.

### Input Fields & Search Bars
- **Background:** Surface Soft (`#111827`)
- **Idle Border:** 1px Slate Hairline (`#1f293d`)
- **Focus Border:** 1px Emerald Accent (`#09815c`) with an sharp, unblurred outline state.

---

## 4. Metric Grids, Lists, & High-Density Tables

For dashboards, static analytical reports, and list-based layouts:

| Layout Category | Default Style | Highlight Strategy |
| :--- | :--- | :--- |
| **Grid Boundaries** | 1px Hairline (`#1f293d`) | No box shadows; clean spacing |
| **Active States** | Subdued Emerald Text | Used for positive deltas (+X.XX%) or active flows |
| **Table Headings** | Uppercase Sans-Serif | Light grey-blue with generous padding |
| **Value Presentation** | High-density clean layout | Monospace/Inter styling for readability |

---

## 5. Conversational UI & Chatbot Archetypes

For chat widgets, conversational assistants, and interactive logs:

### Chat Feed Area
- **Canvas Base:** Obsidian Slate-Blue (`#0a0e17`)

### User Message Balloon
- **Background:** Surface Soft (`#111827`)
- **Border:** 1px Slate Hairline (`#1f293d`)
- **Alignment:** Right-aligned with clean text-wrapping and standard margins.

### Agent / Chatbot Response Balloon
- **Background:** Surface Soft (`#111827`)
- **Border:** 1px Subdued Emerald (`#09815c`) or Sage Muted (`#86efac`) to define system narrative authority.
- **Alignment:** Left-aligned, paired with a small monospace status line (e.g. `System Node: Active`).

---

## 6. Design System Compliance & Core Rules

### Do:
- [x] **DO** maintain the Obsidian Slate-Blue (`#0a0e17`) canvas as the absolute background floor across all digital interfaces.
- [x] **DO** use Subdued Emerald Green (`#09815c`) as the primary visual focus indicator for navigation, button states, active chat headers, and callouts.
- [x] **DO** pair the elegant Petrona serif layout headlines with generous vertical spacing to respect high-end editorial pacing.
- [x] **DO** construct sharp layouts utilizing explicit `1px` boundaries instead of blurred, heavy dropshadows.

### Don't:
- [ ] **DON'T** introduce warm copper, terracotta, active orange, or glowing yellow highlight layers.
- [ ] **DON'T** rely on blurred drop shadows for dark elements. Keep layouts clean with sharp 1px Hairline (`#1f293d`) borders.
- [ ] **DON'T** use bright neon greens. Keep all emerald highlights tuned precisely to the muted depth of `#09815c`.
