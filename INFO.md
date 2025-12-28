# CURSOR PROMPT — Tezpur University • Department of Design (Gestalt-based Website)

You are building a **simple, attractive, modern, university-themed** website for the **Department of Design, Tezpur University**.
They will judge the **look & feel**, not the code quality. Make it visually premium and “student professional”.

## Goal
Create a **single-page** responsive website (desktop + mobile) that clearly demonstrates **Gestalt principles** in the layout:
- **Proximity** (group related items)
- **Similarity** (consistent card styles, icons, tags)
- **Common Region** (boxed sections)
- **Figure–Ground** (strong contrast, layered backgrounds)
- **Continuity** (guided reading flow, lines/paths)
- **Closure** (implied shapes via spacing/borders)
- **Hierarchy** (typography scale + spacing)

## Tech constraints
- Use only: **HTML + CSS + JS**
- Use CDNs if needed (preferred):
  - Tailwind via CDN OR Bootstrap (choose ONE)
  - Google Fonts
  - Icons (Font Awesome or Lucide)
  - Optional animation helper (AOS or GSAP)
- No React, no build tools.

## Assets
The user will provide 2 PNG logos. In code, assume these filenames in `/assets/`:
- `/assets/tu_logo.png`  (Tezpur University logo)
- `/assets/design_dept_logo.png` (Department of Design logo)

Also use a few high-quality placeholder images (Unsplash) for hero/gallery.

---

## Deliverables (create these files)
1. `index.html`
2. `styles.css`
3. `script.js`
4. `README.md` (short: how to run + what Gestalt principles were used)

---

## Visual style direction (VERY IMPORTANT)
Make it feel like a **modern university + design department**:
- Clean grid, generous whitespace, soft shadows, rounded corners
- Elegant gradients (not too neon), subtle patterns, premium typography
- “Design-school” vibe: minimal but creative, with micro-interactions
- Include a **light/dark toggle** (small, classy)
- Add subtle scroll animations (AOS recommended)

Color suggestion:
- Primary: deep navy / indigo
- Accent: warm saffron / orange (very subtle) + teal highlights
- Background: off-white for light mode; near-black for dark mode

Typography:
- Headings: `Poppins` or `Space Grotesk`
- Body: `Inter`

---

## Content (use this structure)

### 1) Sticky Navbar
Left: TU logo + Department logo (small)  
Right: links with smooth scroll:
- Home
- About
- Programs
- Facilities
- Contact

Add a primary CTA button: **“Apply / Enquire”** (scrolls to contact)

### 2) Hero Section (Figure–Ground + Hierarchy)
- Big headline: “Department of Design”
- Subtext: design thinking + innovation + human-centered learning
- Two CTAs: “Explore Programs” + “View Facilities”
- Right side: a clean image collage or single hero photo inside a rounded container
- Add a “floating” stats row (Common Region):
  - “Programs”
  - “Studios”
  - “Workshops”
  - “Student Projects”
(Use nice counters that animate on scroll)

### 3) Gestalt Showcase Strip (Proximity + Similarity)
A horizontal row of 6 small “principle cards”, each with icon + label:
Proximity, Similarity, Continuity, Closure, Figure–Ground, Common Region.  
On hover: highlight and show a 1-line tooltip.

### 4) About Section (Continuity)
Two-column:
- Left: short story about department vision
- Right: 3 feature cards (Similarity):
  - “Design Thinking”
  - “Studio Culture”
  - “Interdisciplinary Learning”

### 5) Programs Section (Common Region + Similarity)
Use 3 premium cards:
- **B.Des**
- **M.Des**
- **Integrated B.Des + M.Des**
Each card includes:
- Duration (placeholder)
- Key focus areas (3 bullets)
- A small “tag row” (UI chips)

### 7) Facilities / Labs (Closure)
Use a neat “gallery-like” grid:
- 6 cards with images and titles:
  - Design Studio
  - Prototyping Lab
  - Digital Media Lab
  - Materials Library
  - Seminar Room
  - Exhibition Space

Use spacing + borders to create implied shapes (closure).


### 9) News / Notices (Proximity)
Right side list style (like modern bulletin):
- 5 items with date + title
- “View all” button (non-functional)

### 10) Contact Section (Common Region)
- Left: Address block (placeholder text is fine)
- Right: a modern enquiry form:
  - Name, Email, Subject, Message
  - Submit shows toast “Message sent (demo)”

Also include social icons row.

### 11) Footer
Minimal footer with both logos + copyright.

---

## Interactions (JS requirements)
- Smooth scroll for navbar links
- Active section highlight in navbar (intersection observer)
- Light/Dark toggle with localStorage
- Animated counters on scroll
- Modal popup for “Student Work” cards
- Filter faculty cards by category
- Simple toast notifications (custom)

---

## Libraries (use these CDNs)
Choose Tailwind CDN for fast modern styling + write small custom CSS for extras.

### Include in `index.html`
- Tailwind CDN: `https://cdn.tailwindcss.com`
- Google Fonts (Inter + Space Grotesk)
- Icons: Font Awesome CDN
- AOS animations:
  - CSS: `https://unpkg.com/aos@2.3.1/dist/aos.css`
  - JS:  `https://unpkg.com/aos@2.3.1/dist/aos.js`

---

## Implementation notes
- Keep everything in one page.
- Make it super clean, premium, and “design department”.
- Use consistent spacing and components so Gestalt principles are obvious.
- Add subtle background pattern (CSS) using radial gradients or SVG data URI.
- Ensure responsive behavior: navbar collapses to hamburger menu on mobile.

---

## Output format
Generate the full code for all files:
- `index.html` (complete)
- `styles.css` (complete)
- `script.js` (complete)
- `README.md` (complete)

Do not add extra explanation outside the files—just output the files with clear separators like:

### index.html
```html
...
```

### styles.css
```css
...
```

### script.js
```js
...
```

### README.md
```md
...
```
