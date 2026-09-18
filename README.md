# Habeeb Dev Portfolio Website

This project is a modern portfolio and service website for Habeeb Dev.

## Included pages
- index.html — main homepage
- work.html — project/work page
- contact.html — contact form and social links
- styles.css — styling for the whole site

## Features
- Hero section with branding and CTAs
- About Me section with creative design
- Service cards and animated marquee
- Work page with project examples
- Contact form connected to Formspree
- WhatsApp, Telegram, email, and phone contact options
- Responsive dark premium design

## Run locally
Open any of the HTML files in a browser, or use a local web server.

Example:

```bash
cd my-landing-page
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Deploy to GitHub Pages
1. Push this folder to a GitHub repository.
2. Open your GitHub repository.
3. Go to Settings > Pages.
4. Under Source, select the main branch.
5. Choose the root folder or / (root).
6. Save.

Your website will be published at:

```text
https://<your-username>.github.io/<your-repo-name>/
```

## Git commands to push to GitHub

```bash
git init
git add .
git commit -m "Initial portfolio website upload"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

## Contact form setup
The contact page is connected to Formspree:

```text
https://formspree.io/f/xvkpndww
```

If you want to keep the form working, make sure the Formspree form endpoint stays active in your account.
