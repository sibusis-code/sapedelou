# Sapedelou Business Consulting — Website

This is a simple static site built from the provided flyer. Features:

- Mobile-first responsive layout
- Smooth scrolling navigation with active highlight
- SVG icons for fast load
- Hamburger mobile navigation
- Contact form that attempts to POST to Formspree and falls back to opening the user's email client

How to view locally

1. Open `index.html` in your browser (double-click it or open via your code editor).
2. In browser DevTools (F12) use the device toolbar to preview mobile.

Form setup (optional)

- Sign up at Formspree (https://formspree.io) and create a form. Replace the `action` in `index.html` (form `action="https://formspree.io/f/yourFormID"`) with your Formspree endpoint.
- If you don't want a service account, the form will fall back to opening the user's email client (mailto) automatically.

Deploying

- GitHub Pages: create a repo and push this folder. In repo settings enable GitHub Pages from the `main` branch (root). The site will be served at `https://<your-username>.github.io/<repo>/`.

What I can do next

- Replace SVG placeholders with uploaded images you provide.
- Add analytics or a server-backed contact endpoint.
- Prepare a minified production bundle and a simple CI deploy workflow.

If you'd like me to deploy this to GitHub Pages or prepare a ZIP for the client, tell me and I'll do it.