# GSS 1.1

A professional website built for Cloudflare Pages deployment.

## About

GSS 1.1 provides professional web solutions with cutting-edge technology. This site is optimized for deployment on Cloudflare's global network, ensuring fast, secure, and reliable service delivery.

## Features

- ⚡ Lightning-fast performance with Cloudflare CDN
- 🔒 Enterprise-grade security
- 🌍 Global reach from 300+ cities worldwide
- 📱 Fully responsive design
- 🎨 Modern, clean UI

## Deployment

### Cloudflare Pages

This site is ready to deploy to Cloudflare Pages:

1. Push your code to GitHub
2. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
3. Connect your GitHub repository
4. Configure build settings:
   - **Build command**: Leave empty (static site)
   - **Build output directory**: `.` (root directory)
5. Deploy!

### Manual Deployment

You can also deploy manually using Wrangler CLI:

```bash
npm install -g wrangler
wrangler pages publish .
```

## Local Development

To preview the site locally:

```bash
# Using Python (recommended)
python3 -m http.server 8000

# Then open http://localhost:8000 in your browser
```

Or use npm:

```bash
npm run dev
```

## Project Structure

```
gss_1.1/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── wrangler.toml       # Cloudflare configuration
├── package.json        # Project metadata
└── README.md          # This file
```

## Configuration

The site includes optimized configurations for Cloudflare:

- **Security headers**: X-Frame-Options, X-Content-Type-Options, etc.
- **Cache control**: Optimized caching for static assets
- **Redirects**: SEO-friendly URL redirects

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - Feel free to use this project for your own purposes.

## Contact

For questions or support, please use the contact form on the website.

---

**Powered by Cloudflare** 🚀
