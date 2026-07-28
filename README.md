# Mahakal Pure — Starter Website

This repository now contains a small, responsive static website (HTML + CSS + Bootstrap) suitable for a packaged drinking water business.

Files added/updated

- index.html — Landing page with hero, featured products, and call-to-action (updated packaging & colors)
- about.html — Company story, quality and values
- products.html — Product listings and packaging: 1 L (box of 12), 500 ml (box of 24), 200 ml (box of 48), 20 L jar (single)
- contact.html — Contact form stub and contact details (business hours updated to 9:00 AM - 7:00 PM)
- assets/css/styles.css — Updated color scheme to white + purple (#7c0398) and dark text
- assets/img/* — Simple SVG placeholders (logo, bottle, product images)

How to preview locally

1. Clone the repo (if not already):
   git clone https://github.com/mahakalpure/mahakalpure.git
2. Open the folder and run a simple local server, e.g.:
   python -m http.server 8000
3. Open http://localhost:8000 in your browser

Enable GitHub Pages

1. Go to repository Settings → Pages
2. Select branch: main and folder: / (root)
3. Save — the site will be published at https://<your-username>.github.io/mahakalpure/ (may take a minute)

Next steps / optional upgrades

- Replace placeholder images with your product photos and logo (assets/img/)
- Update contact details and business hours in contact.html
- Add real certifications and lab reports in about.html
- Wire the contact form to Formspree, Netlify Forms, or another backend
- Add a CNAME for a custom domain

If you want, I can next:
- Wire the contact form to Formspree/Netlify and show the changes
- Add pricing and a simple order form (no payment) or full e-commerce integration
- Create a CNAME and configure the repo for a custom domain

