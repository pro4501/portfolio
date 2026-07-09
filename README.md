# Pratham's Cybersecurity Portfolio

A case-file themed portfolio showcasing experience in cybersecurity, digital forensics, and related technical work. The site presents professional credentials through a distinctive investigative/crime scene aesthetic.

## Overview

This is a single-page HTML portfolio with a unique crime scene aesthetic. Visitors navigate through sections styled as case file exhibits, complete with:

- Animated crime scene tape dividers
- Evidence-style project cards with cryptographic hash visualizations
- A hanging ID badge with lanyard animation
- Scanline and chalk outline effects

## Project Structure

```text
portfolio/
├── index.html    # Single-page portfolio (main file)
└── README.md     # This file
```

## Sections

The portfolio contains the following sections, accessible via the tab navigation:

| Section | ID | Description |
|---------|-----|-------------|
| Profile | `#profile` | Hero introduction and background summary |
| Experience | `#experience` | Professional work history |
| Projects | `#projects` | Notable technical projects and achievements |
| Skills | `#skills` | Technical skills and tools (SOC, development, governance) |
| Education | `#education` | Academic credentials |
| Contact | `#contact` | Contact information and call-to-action |

## Technologies Used

- **HTML5** — Semantic markup with ARIA labels for accessibility
- **CSS3** — Custom properties, animations, responsive design
- **JavaScript** — Intersection Observer for scroll effects and tab tracking
- **Google Fonts** — Space Grotesk, Inter, JetBrains Mono, and Caveat

## Local Development

No build process is required. To view the portfolio:

```bash
# Open directly in a browser
open index.html

# Or serve with a simple HTTP server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Customization

### Updating Content

All portfolio content is in `index.html`. Key areas to update:

1. **Personal information** — Search for "Pratham" and replace with your name
2. **Contact details** — Update the email in the contact section
3. **Experience and projects** — Modify the cards within each section
4. **Skills** — Update the manifest grid in the Skills section

### Styling

CSS custom properties are defined at the top of the `<style>` block:

```css
:root {
  --ink: #0b0e14;          /* Primary background */
  --paper: #ede9de;        /* Card backgrounds */
  --amber: #e8a33d;       /* Accent color */
  --teal: #4fb8ae;         /* Secondary accent */
  --stamp-red: #c1443c;   /* Alert/warning color */
}
```

## Accessibility

- Respects `prefers-reduced-motion` — animations are disabled for users who prefer reduced motion
- Semantic HTML structure with proper heading hierarchy
- ARIA labels on decorative elements
- Sufficient color contrast ratios

## Browser Support

Modern browsers (Chrome, Firefox, Safari, Edge). The site uses:

- CSS Custom Properties
- CSS Grid and Flexbox
- Intersection Observer API
- CSS animations with `@keyframes`

## License

This portfolio template is open for customization and use.
