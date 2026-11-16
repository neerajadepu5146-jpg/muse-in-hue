# muse.in.hue

**Every Hue Holds a Story.**

muse.in.hue is an online storefront for original art by Vineela. Browse themed collections like *Night Skies* and *Seaside Escapes*, or request a custom piece made just for you.

🔗 **Live site:** [muse-in-hue.netlify.app](https://muse-in-hue.netlify.app)

<!-- Add a screenshot: upload screenshot.png to this repo, then uncomment the line below -->
<!-- ![muse.in.hue screenshot](screenshot.png) -->

## Features

- **Shop and collections:** curated artwork organised by theme, with filtering
- **Cart, wishlist and checkout:** a complete shopping flow on a single page
- **UPI / QR payments:** QR code generation for easy payment
- **Custom art requests:** an enquiry form for commissioned pieces
- **Contact form:** messages open as a pre-filled email
- **Welcome offer:** 10% off a first order
- **Responsive layout:** adapts to desktop, tablet and mobile screens
- **SEO ready:** `sitemap.xml`, `robots.txt` and Google Search Console verification

## Built with

- HTML, CSS and vanilla JavaScript (single-page site)
- [Google Fonts](https://fonts.google.com/): Cormorant Garamond and DM Sans
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) for QR generation
- Hosted on [Netlify](https://www.netlify.com/)

## Project structure

```
.
├── index.html                  # The entire site (markup, styles, scripts)
├── sitemap.xml                 # Sitemap for search engines
├── robots.txt                  # Crawler rules
└── google9c5c43ed7700ec9c.html # Google Search Console verification
```

## Run locally

No build step needed.

```bash
git clone https://github.com/YOUR-USERNAME/muse-in-hue.git
cd muse-in-hue
```

Then open `index.html` in your browser. Or serve it locally:

```bash
npx serve .
```

## Deployment

The site is deployed on Netlify. To deploy your own copy, connect this repository in Netlify (**Add new site → Import an existing project**). No build command is required, and the publish directory is the repo root.

## Sections

Home · Shop · Collections · Custom Art · Our Story · Contact

## Copyright

© 2026 muse.in.hue. Original art by Vineela. All artwork and images are the property of the artist and may not be copied, reproduced or used without permission.
