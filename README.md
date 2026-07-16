# Website

A clean, modern static website built with HTML, CSS, and JavaScript.

## Project Structure

```
├── index.html          # Home page
├── about.html          # About page
├── contact.html        # Contact page
├── styles.css          # Global styles
├── DESIGN.md           # Design system documentation
├── vercel.json         # Vercel deployment config
├── package.json        # Project metadata (optional)
└── README.md           # This file
```

## Development

Simply open any `.html` file in your browser. There's no build process required.

For local development with a simple HTTP server:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server
```

Then visit `http://localhost:8000`

## Deployment to Vercel

### Option 1: Via Git (Recommended)

1. Push this repository to GitHub:
   ```bash
   git remote add origin https://github.com/your-username/website.git
   git branch -M main
   git push -u origin main
   ```

2. Import to Vercel:
   - Visit [vercel.com](https://vercel.com)
   - Click "New Project"
   - Select your GitHub repository
   - Click "Deploy"

### Option 2: Vercel CLI

```bash
npm i -g vercel
vercel
```

## Customization

- Edit page content in `index.html`, `about.html`, and `contact.html`
- Update colors and typography in `DESIGN.md` and `styles.css`
- Update company name in the navbar and hero sections
- Customize the contact form endpoint as needed

## License

MIT
