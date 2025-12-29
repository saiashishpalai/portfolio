# Portfolio Website

A minimalist, black and white portfolio website with light/dark theme toggle.

## Features

- ✨ Clean, minimalist design
- 🌓 Light/Dark theme toggle with persistent preference
- 📱 Fully responsive design
- ⚡ Fast and lightweight
- 🎨 Beautiful typography and animations

## Tech Stack

- Pure HTML, CSS, and JavaScript
- No build process required
- Can be deployed to any static hosting service

## Deployment

### Vercel (Recommended)

1. Sign up at [vercel.com](https://vercel.com) with GitHub
2. Import this repository
3. Deploy (no build settings needed)
4. Add custom domain in project settings

### Netlify

1. Sign up at [netlify.com](https://netlify.com) with GitHub
2. Import this repository
3. Deploy (publish directory: `/`)
4. Add custom domain in site settings

### GitHub Pages

1. Go to repository Settings → Pages
2. Select `main` branch and `/` folder
3. Create `CNAME` file with your domain
4. Update DNS records

## Local Development

Simply open `index.html` in a web browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## Custom Domain Setup

After deploying, update your DNS records:

- **A Records**: Point to hosting provider's IP addresses
- **CNAME**: Point to hosting provider's domain
- Wait 5-60 minutes for DNS propagation

## License

MIT License

