# Salesforce Embedded Messaging Demo (GitHub Pages)

This repository provides a minimal, static test page for Salesforce Embedded Messaging, suitable for quick prototyping and sandbox testing. It is designed to be hosted on GitHub Pages.

## What is this?
A simple `index.html` that loads the Salesforce Embedded Messaging widget, styled as a basic support/contact page. No frameworks, no build tools — just static HTML and CSS.

## How to use
1. **Fork or clone this repo.**
2. **Enable GitHub Pages:**
   - Go to your repo's **Settings** → **Pages**.
   - Under "Source", select the `main` branch (or `master`) and `/ (root)` folder.
   - Save. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.
3. Visit your published site. The Salesforce Embedded Messaging widget should appear (bottom right).

## Salesforce Setup Gotchas
- **Allowed Domains:**
  - You must add your GitHub Pages domain (e.g., `https://your-username.github.io`) to the **Embedded Service Deployment**'s Allowed Domains in Salesforce Setup.
  - Otherwise, the widget will not load due to CORS/iframe restrictions.
- **CORS:**
  - Make sure your Salesforce org allows requests from your GitHub Pages domain.
- **Sandbox URLs:**
  - This demo uses sandbox endpoints. For production, update the widget snippet with your production URLs and org IDs.
- **HTTPS Required:**
  - GitHub Pages is always HTTPS. Your Salesforce deployment must also be HTTPS.

## Customization
- Edit `index.html` to adjust branding, text, or widget configuration as needed.

---

**This is a test/demo only. Do not expose sensitive data or credentials.**
