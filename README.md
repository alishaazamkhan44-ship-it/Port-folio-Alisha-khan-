# ALISHA KHAN – Personal Website

> Building Intelligent Products That Ship.

Portfolio site for **ALISHA KHAN**, AI Expert, AI Engineer and Founder (Kot Addu, Pakistan). Plain HTML, CSS and JavaScript: no build step, no dependencies.

## Features
- Sections: Hero, About, Expertise, Ventures, Projects (filterable), Tech stack, Experience, Speaking and writing, Testimonials, Work with me, Contact
- Animated canvas hero showing an AI agent loop (Data → Retrieve → Reason → Act → Evaluate)
- Light/dark theme toggle (remembers your choice), responsive mobile menu
- Accessible: skip link, focus styles, ARIA labels, reduced-motion support
- Contact form validates input and opens the visitor's email app
- SEO: meta tags, Open Graph, Twitter card, schema.org JSON-LD

## Structure
```
├── index.html          # Page markup
├── css/styles.css      # Design tokens and styles
├── js/data.js          # Your content (ventures, projects, stack, timeline…)
├── js/main.js          # Rendering, theme, menu, form, hero animation
├── 404.html            # Custom not-found page
├── robots.txt
├── assets/             # favicon.svg, apple-touch-icon.png, og-image.png
└── .github/workflows/pages.yml   # Auto-deploy to GitHub Pages
```

## Edit your content
Open `js/data.js`. Everything marked `[EDIT]` is a placeholder: add your other four companies, project outcomes, experience, talks and real testimonials. Also replace the `#` links for LinkedIn, GitHub and X in the footer of `index.html`, and swap the monogram image in the About section for your photo.

## Run locally
```bash
git clone https://github.com/<your-username>/alisha-khan-website.git
cd alisha-khan-website
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy (GitHub Pages)
1. Push to the `main` branch.
2. In the repo go to **Settings → Pages → Source → GitHub Actions**.
3. The included workflow publishes the site at `https://<your-username>.github.io/alisha-khan-website/`.

## License
MIT © 2026 ALISHA KHAN
