# ASRONEXE website

Static site: plain HTML + CSS, no build step.

## Pages
- `index.html` — Home
- `services.html` — Services
- `case-study.html` — Case study template (duplicate per project)
- `careers.html` — Careers

## Run locally
Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000

## Customise
- Accent colour: `--accent` in `styles.css`.
- Replace every `[BRACKETED]` placeholder (client logos, stats, address, email, phone, testimonials, tech stacks, benefits).
- Forms (contact on Home, application on Careers) have no backend yet — point them at your form handler (e.g. Formspree, a serverless function, or your CRM) and add `name` attributes / `action`.

## Deploy
Upload the folder to any static host: Netlify, Vercel, GitHub Pages, AWS S3 + CloudFront, or cPanel hosting.
