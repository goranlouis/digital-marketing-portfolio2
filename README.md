# Goran Louis Stephan — Digital Marketing Portfolio

A dark-mode personal portfolio website for a digital marketing & sales specialist.
Generated from Stitch and organized for local development.

---

## Tech Stack

- **HTML5** — static, no build step required
- **Tailwind CSS** — loaded via CDN with a custom inline config
- **Fonts** — Space Grotesk (headlines) + Inter (body) via Google Fonts
- **Icons** — Material Symbols Outlined via Google Fonts CDN

---

## Project Structure

```
digital-marketing-portfolio/
├── index.html                  ← Entry point (redirects to pages/home.html)
├── README.md
├── pages/
│   ├── home.html               ← Home / Hero page
│   ├── portfolio-gallery.html  ← Bento-grid portfolio
│   ├── services-contact.html   ← Services & contact form
│   └── design-plan.html        ← Stitch design plan doc
├── assets/
│   └── images/
│       ├── home.webp
│       ├── portfolio-gallery.webp
│       └── services-contact.webp
└── stitch/                     ← Raw Stitch exports (source of truth)
    ├── code/
    └── images/
```

---

## Running Locally

```bash
# Python (no install needed)
python -m http.server 3000
```

Then open: [http://localhost:3000](http://localhost:3000)

| Page | URL |
|------|-----|
| Home | http://localhost:3000/pages/home.html |
| Portfolio Gallery | http://localhost:3000/pages/portfolio-gallery.html |
| Services & Contact | http://localhost:3000/pages/services-contact.html |
| Design Plan | http://localhost:3000/pages/design-plan.html |

---

## Design System

- **Color mode:** Dark
- **Primary accent:** `#81ecff` (cyan)
- **Background:** `#0e0e0e`
- **Headline font:** Space Grotesk
- **Body font:** Inter
- **Roundness:** Sharp (`0.125rem` default)
- **Creative North Star:** *The Kinetic Command* — editorial asymmetry, tonal depth, glassmorphism nav
