# Pratham Brahmbhatt — Cybersecurity Portfolio

Case-file portfolio for Pratham Brahmbhatt, served by GitHub Pages at [pro4501.github.io/portfolio](https://pro4501.github.io/portfolio/). The page keeps a dark forensic evidence-board layout: folder-tab navigation, crime-scene tape, a hanging ID badge, and project cards pinned like exhibits.

Facts on the page follow the CV. Nothing here is a placeholder profile.

## Project structure

```text
portfolio/
├── index.html
├── README.md
└── images/
    ├── soc-platform.jpg
    ├── chain-of-custody.jpg
    ├── kc7-threat-hunt.jpg
    └── hospitality-portal.jpg
```

Image paths are relative (`images/...`) so they resolve under `/portfolio/` on GitHub Pages.

## Sections

| Section | ID | What it shows |
|---------|-----|----------------|
| Profile | `#profile` | London (Wembley) background, focus areas, and current status |
| Experience | `#experience` | Work history, newest first |
| Projects | `#projects` | Evidence-board exhibits |
| Skills | `#skills` | Tools, frameworks, and training profiles |
| Education | `#education` | MSc and BSc at Middlesex University |
| Contact | `#contact` | Email, LinkedIn, and GitHub |

## Experience

Newest first:

- **Mercor** — Generalist Expert (Contractor), remote, Aug–Oct 2026. AI-related project work.
- **Rynex Security** — Penetration Testing / Red Team Intern, Jul–Aug 2026. Three authorised engagements: a public-facing website, a Metasploitable target, and an OS dump supplied by Rynex.
- **Bugcrowd** — Security Researcher (handle `pratham4501`). Settle vulnerability disclosure programme: invoice amount tampering (triaged P4) and account enumeration (triaged).
- **Yatri India** — General Manager, Wembley, Dec 2024–Sep 2026 (previously Assistant Manager, Sep 2022–Nov 2024).

## Education

- **MSc Cybersecurity & Emerging Threats**, Middlesex University — ongoing, finishing by July 2027.
- **BSc Cybersecurity & Digital Forensics**, Middlesex University — 2020–2024, 2:1.

The MSc is not labelled part-time or full-time.

## Projects

| Exhibit | Image | Link |
|---------|--------|------|
| Multi-Agent SOC Analyst Platform | `images/soc-platform.jpg` | [github.com/pro4501/soc-alert-triage](https://github.com/pro4501/soc-alert-triage) |
| Chain of Custody Management System | `images/chain-of-custody.jpg` | [github.com/pro4501/chain-of-custody](https://github.com/pro4501/chain-of-custody) |
| KC7 Threat Hunting Investigations | `images/kc7-threat-hunt.jpg` | No public repository |
| Hospitality Staff Training Portal | `images/hospitality-portal.jpg` | No public repository |
| Nmap Practice Range | None supplied | [Repository](https://github.com/pro4501/nmap-practice-range) and [live demo](https://pro4501.github.io/nmap-practice-range/) |

## Training

- [TryHackMe — 08prathambarot](https://tryhackme.com/p/08prathambarot)
- [Hack The Box Academy](https://profile.hackthebox.com/profile/01a162d7-4b64-7167-b3c1-ba81b749f5f5)
- Completed AI Security University courses, including MCP Security Fundamentals, AI Security for Everyone, and Zero Touch API Governance.

## Contact

Open to SOC analyst, penetration testing, and GRC roles.

- Email: [08prathambarot@gmail.com](mailto:08prathambarot@gmail.com)
- LinkedIn: [linkedin.com/in/prathambrahmbhatt](https://www.linkedin.com/in/prathambrahmbhatt/)
- GitHub: [github.com/pro4501](https://github.com/pro4501)

External links use `target="_blank"` and `rel="noopener"`.

## Local preview

No build step. From the repository root:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Styling

CSS custom properties live at the top of the `<style>` block in `index.html`:

```css
:root {
  --ink: #0b0e14;          /* Primary background */
  --paper: #ede9de;        /* Card backgrounds */
  --amber: #e8a33d;        /* Accent color */
  --teal: #4fb8ae;         /* Secondary accent */
  --stamp-red: #c1443c;    /* Alert/warning color */
}
```

Exhibit photographs use `max-width: 100%` and `height: auto` inside a paper mat so they scale on narrow screens.

## Accessibility

- `prefers-reduced-motion` disables decorative animation
- Heading hierarchy follows the case-file sections
- Decorative marks are `aria-hidden`
- Exhibit images have descriptive alt text

## Browser support

Current Chrome, Firefox, Safari, and Edge. The page uses CSS custom properties, Grid, Flexbox, Intersection Observer, and CSS animations.
