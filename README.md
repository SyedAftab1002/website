# Transways India Corporation — Website

A modern, light-themed website for a pan-India trucking and logistics company. Built with HTML, CSS, and JavaScript, ready to deploy on Vercel.

## About Transways India

Transways India Corporation connects shippers with verified truck owners across India. The platform provides transparent pricing, real-time tracking, and reliable same-day-to-next-day delivery across 500+ cities.

**Features:**
- Full Truck Load (FTL) and Part Load services
- Live GPS tracking and digital proof-of-delivery
- 98% on-time delivery rate
- 24/7 dispatch support
- Pan-India network with verified partners

## Project Structure

```
├── index.html          # Home page (hero, services, coverage, why us)
├── about.html          # Company story, mission, values, impact
├── contact.html        # Contact form and support channels
├── styles.css          # Modern light-theme design system
├── DESIGN.md           # Complete design system documentation
├── vercel.json         # Vercel deployment configuration
└── README.md           # This file
```

## Design System

The website uses a **light, modern color theme** with:
- **Primary Blue**: `#0066cc` — main brand color
- **Light Backgrounds**: Off-white and light gray (clean, spacious feel)
- **Professional Typography**: System fonts, generous spacing
- **Responsive Layout**: Mobile-first, works on all devices

See `DESIGN.md` for complete documentation.

## Local Development

No build process required. Simply run a local HTTP server:

```bash
# Python 3
python -m http.server 8000

# Node.js / npm
npx http-server

# Bun
bun serve
```

Then visit `http://localhost:8000`

## Deployment to Vercel

The website is already pushed to [GitHub](https://github.com/SyedAftab1002/website). To deploy on Vercel:

1. Go to [vercel.com](https://vercel.com)
2. Click **"New Project"**
3. Select the **website** repository from GitHub
4. Click **"Deploy"**

Vercel will auto-detect the static site and deploy it instantly. Your site will be live at `website-xxxxx.vercel.app`.

## Customization

### Update Content
- **Company Name**: Edit "Transways India" in navbar (all pages)
- **Contact Info**: Update phone, email in `contact.html`
- **Office Address**: Edit in `contact.html`
- **Stats**: Update numbers in `index.html` (shipments, partners, etc.)

### Update Design
- **Colors**: Edit CSS variables in `styles.css` (lines 1-15)
- **Fonts**: Change font-family in `styles.css` line 14
- **Logo**: Replace truck emoji in navbar with your logo

### Update Services
Edit the service cards in `index.html` (#services section):
- Change service titles and descriptions
- Update service icons (currently using emojis)

## Features

✅ **Mobile Responsive** — Works perfectly on all screen sizes
✅ **Modern Design** — Clean, professional, easy to navigate
✅ **Contact Form** — Ready-to-use with form submission
✅ **SEO Friendly** — Semantic HTML, proper meta tags
✅ **Performance** — Fast static site, no database needed
✅ **Vercel Ready** — One-click deployment

## Support

For questions or issues, contact the development team or refer to the `DESIGN.md` for technical details.

## License

© 2026 Transways India Corporation. All rights reserved.
