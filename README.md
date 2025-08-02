# PeachPapaya Privacy Policy

A static privacy policy page built with Astro for optimal SEO and web crawler accessibility.

## Features

- ✅ Static site generation for fast loading
- ✅ SEO optimized with proper meta tags
- ✅ Web crawler friendly
- ✅ Zero JavaScript by default
- ✅ Responsive design
- ✅ Security headers configured

## Pages

- **Home** (`/`) - Simple landing page with contact info
- **Privacy Policy** (`/privacy`) - Privacy policy content
- **Terms & Conditions** (`/terms`) - Service terms and agreements
- **Data Deletion** (`/data-deletion`) - Instructions for data deletion requests

## Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment to Vercel

1. **Push to GitHub**: 
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Deploy to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Vercel will automatically detect it's an Astro project
   - Deploy!

3. **Update Configuration**:
   - After deployment, update the `site` URL in `astro.config.mjs` with your actual Vercel URL
   - Update the sitemap URL in `public/robots.txt`

## SEO Features

- Static HTML generation
- Proper meta tags
- Robots.txt configured
- Security headers
- Fast loading times

## File Structure

```
src/
  pages/
    index.astro         # Home page
    privacy.astro       # Privacy policy
    terms.astro         # Terms & conditions
    data-deletion.astro # Data deletion instructions
public/
  robots.txt            # SEO configuration
vercel.json             # Vercel deployment config
astro.config.mjs        # Astro configuration
```

## Customization

To update content, edit the corresponding `.astro` files in `src/pages/`. The pages use inline CSS for simplicity, but you can extract styles to a separate file if needed. 