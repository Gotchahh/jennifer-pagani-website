# Jennifer Pagani — Make-up Artist Website

One-page portfolio website for **Jennifer Pagani**, a make-up artist based in Udine, Italy.

🔗 **Live:** https://jennifermua.com

## Overview

A lightweight, mobile-first showcase site built as a single self-contained HTML file.
It presents Jennifer's services, portfolio galleries and contact channels, with a
warm, elegant visual identity.

## Tech stack

- **HTML / CSS / JavaScript** (vanilla, no framework, no build step)
- **Fonts:** Cormorant Garamond (headings) + Inter (body), via Google Fonts
- **Hosting:** Cloudflare Workers (static assets) with automatic HTTPS
- **Domain:** jennifermua.com (Cloudflare Registrar)

## Features

- Fully responsive, mobile-first layout
- Sticky navigation with pure-CSS mobile menu
- Full-screen hero section
- Sections: Home, About (Chi sono), Services (Servizi), Portfolio, Contact
- Horizontal swipe galleries (Spose, Cerimonie & eventi, Glam & sera, Lezioni)
- Scroll-reveal animations (respect `prefers-reduced-motion`)
- Fixed WhatsApp quick-contact bar + Instagram link

## Project structure

The whole site currently lives in a single `index.html` file, with images
embedded as base64 data URIs — so it works with zero external dependencies.

> Possible future improvement: extract images into a separate `/assets` folder
> to reduce the HTML size and speed up loading.

## Local development

No build step required. Just open `index.html` in a browser, or use a live-reload
tool such as the **Live Server** extension in VS Code.

## Deployment

The site is deployed on Cloudflare. To publish an update, upload the new
`index.html` from the Cloudflare dashboard (**Workers & Pages → New deployment**).
The domain and HTTPS certificate stay unchanged.

---

© Jennifer Pagani. All rights reserved.
