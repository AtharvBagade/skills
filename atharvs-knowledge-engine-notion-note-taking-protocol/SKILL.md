---
name: atharvs-knowledge-engine-notion-note-taking-protocol
description: "This document serves as the operational guide (skill.md) for transforming raw LLM conversations, technical reports, and intensive research sessions into structured, highly discoverable Notion documentation."
---

# Atharv's Knowledge Engine - Notion Note-Taking Protocol

A comprehensive operational guide for transforming raw LLM conversations, technical reports, and intensive research sessions into structured, highly discoverable Notion documentation.

---

## Table of Contents

1. [Lifecycle Metadata](#1-lifecycle-metadata)
2. [Hierarchical Domain & Folder Structure](#2-hierarchical-domain--folder-structure)
3. [Page Architecture Layout](#3-page-architecture-layout)
4. [References & External Validation](#4-references--external-validation)

---

## Non negotiables
- No Emojis whatsoever in headings, text or page titles.
- If you find pages with emojis updates them to remove emojis.

## 1. Lifecycle Metadata

Every page must begin with a standardized YAML-style metadata block at the absolute top. This guarantees chronological tracking across shifting technical domains.

```yaml
---
Created At: YYYY-MM-DD
Updated At: YYYY-MM-DD
---
```

---

## 2. Hierarchical Domain & Folder Structure

Organization follows a **Domain-Driven Nested Branching** methodology. The root architecture begins with broad, high-level domains and branches sequentially into atomic subtopics until an ideal category depth is reached. This design maximizes search efficiency and visual organization.

### Root Domains

- **AI:** All things machine learning, neural networks, inference infrastructure, and prompt engineering.
- **Software Engineering:** Systems design, language ecosystems, runtime environments, API protocols, and deployment strategies.
- **Finance:** Market research, quantitative analysis, portfolio management, and asset tracking.

### Standard Taxonomy Examples

To keep pathways predictable, map new pages against these structural blueprints:

- `AI → LLMs → Fundamentals → Math`
- `AI → Infrastructure → Vector Databases → Indexing Mechanics`
- `Software Engineering → Server-Side → Rust → Memory Management`
- `Software Engineering → Server-Side → NestJS → Testing Strategies`
- `Software Engineering → IoT → Protocols → MQTT & State Management`
- `Finance → Equities → Indian Markets → Stock Analysis`

---

## 3. Page Architecture Layout

Every individual page must follow this uniform sequence from top to bottom. Do not deviate from this layout.

### Part I: Context & Navigation

**Summary / Description:** A brief, high-signal paragraph explaining the overarching topic and the specific context covered.

**Table of Contents / Index:** A dedicated navigation list linking to all major subheadings below.

### Part II: Core Content & Deep Dives

For each specific topic covered within the document, organize the data using the following structure:

#### The Core Data
The fundamental breakdowns, architectural logic, and explanations.

#### Deep-Dive Inquiries
The explicit, sequential questions asked during the session to uncover the details (preserving the original context of the discovery).

#### Practical Evidence
Concrete real-world examples found during the discussion, formatted as:

**Code Blocks:** Clean, strongly typed code implementations.

**Mathematical Formulations:** Clean LaTeX syntax for underlying formulas, statistics, or algorithms. Use inline math like $E = mc^2$ or block math for larger equations:

$$\sigma = \sqrt{\frac{1}{N} \sum_{i=1}^{N} (x_i - \mu)^2}$$

### Part III: Cross-Referencing & Rabbit Hole Routing

When a deep dive connects to external internal notes or branches off into unexpected tangents, use these explicit rules:

**Pre-Existing Knowledge Links:** If the topic references an entity or architecture already documented on another page, insert a direct link:
```
[See Pre-Existing Topic](Notion Page Link)
```

**Tangent / Rabbit Hole Navigation:** If an unexpected line of questioning leads down a deep sidebar, document the context but route the reader explicitly:
```
The answers to these tangential questions are fully mapped and covered in the following topics: [Detailed Section/Page Link Name](Notion Link)
```

---

## 4. References & External Validation

To keep the main content clean, never embed raw external URLs or citations directly in the body text. Move all supporting assets to this section at the absolute bottom of the page.

### References

- **Books:** *Book Title*, Author Name (Edition/Year) - Specific chapters.
- **External Webpages:** [Document/Article Title](URL) - Source/Publisher (Access Date).
- **Research Papers:** *Paper Title*, Author et al. (Identifier/Link).