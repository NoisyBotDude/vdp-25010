# Department of Design - Tezpur University Website

A modern, single-page responsive website for the Department of Design at Tezpur University, built to demonstrate Gestalt principles through visual design and layout.

## How to Run

1. **Prerequisites**: No build tools required. Just a modern web browser.

2. **Setup**:
   - Ensure all files are in the same directory:
     - `index.html`
     - `styles.css`
     - `script.js`
     - `assets/` folder containing:
       - `tu_logo.png`
       - `design_dept_logo.png`

3. **Run**:
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```
   - Then navigate to `http://localhost:8000` in your browser

4. **Features to Try**:
   - Toggle light/dark mode using the theme button in the navbar
   - Navigate using the smooth-scrolling menu links
   - Scroll to see animated counters and AOS animations
   - Fill out the contact form to see toast notifications
   - Test responsive design by resizing your browser window

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styles with CSS variables
- **JavaScript (ES6+)** - Vanilla JS for all interactions
- **Tailwind CSS (CDN)** - Utility-first CSS framework
- **Google Fonts** - Inter (body) and Space Grotesk (headings)
- **Font Awesome (CDN)** - Icons
- **AOS (Animate On Scroll)** - Scroll animations

## Gestalt Principles Demonstrated

This website intentionally implements Gestalt principles to create a cohesive and intuitive user experience:

### 1. **Proximity**
- **Location**: Navigation menu, feature cards, news items, facility grid
- **Implementation**: Related items are grouped together with consistent spacing. Navigation links are close to each other, feature cards in the About section are grouped, and news items are clustered together.

### 2. **Similarity**
- **Location**: Program cards, feature cards, facility cards, gestalt showcase strip
- **Implementation**: Consistent card styling, similar icon treatments, and uniform tag chips create visual grouping. Users perceive these similar elements as belonging to the same category.

### 3. **Common Region**
- **Location**: All sections (Hero, About, Programs, Facilities, Contact)
- **Implementation**: Content is organized in clearly defined sections with background colors, padding, and borders. The navbar is a distinct region, as are the footer and each major content section.

### 4. **Figure–Ground**
- **Location**: Hero section, card designs, navbar
- **Implementation**: Strong contrast between foreground content and background. The hero section uses dark text on light background (and vice versa in dark mode). Cards stand out from their backgrounds with shadows and distinct borders.

### 5. **Continuity**
- **Location**: Overall page layout, reading flow, navigation structure
- **Implementation**: The page guides users through a logical flow from top to bottom. Navigation links create continuity between sections. Content flows naturally with consistent typography and spacing.

### 6. **Closure**
- **Location**: Facility grid, program cards layout, gestalt cards
- **Implementation**: Spacing and borders create implied shapes and boundaries. The facility grid uses gaps to suggest organization. Cards with rounded corners and shadows create closed shapes that users perceive as complete units.

### 7. **Hierarchy**
- **Location**: Typography scale, section headers, content organization
- **Implementation**: Clear typographic hierarchy with large headings (Space Grotesk) and body text (Inter). Section titles are larger and bolder, creating a visual hierarchy that guides users through the content.

## File Structure

```
vdp-25010/
├── index.html          # Main HTML structure
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
├── README.md          # This file
└── assets/
    ├── tu_logo.png    # Tezpur University logo
    └── design_dept_logo.png  # Department of Design logo
```

## Key Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Light/Dark mode toggle with localStorage persistence
- ✅ Smooth scroll navigation
- ✅ Active section highlighting in navbar
- ✅ Animated counters on scroll
- ✅ Scroll animations (AOS)
- ✅ Mobile hamburger menu
- ✅ Toast notifications
- ✅ Contact form (demo)
- ✅ Accessible (keyboard navigation, focus states)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Design Philosophy

The website follows a "design-school" aesthetic:
- Clean, minimal design with generous whitespace
- Premium typography (Space Grotesk + Inter)
- Subtle gradients and patterns
- Soft shadows and rounded corners
- Micro-interactions and hover effects
- Modern color palette (indigo, teal, saffron accents)

## Notes

- The contact form shows a demo toast message and doesn't actually send emails
- Images use Unsplash placeholders - replace with actual photos as needed
- All content is placeholder text - update with real department information
- The "View All" button in News section is non-functional as specified

## License

This project is created for the Department of Design, Tezpur University.

---

Built with ❤️ for the Department of Design, Tezpur University
