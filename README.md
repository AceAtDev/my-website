# Mohamed Elshoubky - Portfolio

Static portfolio website optimized for GitHub Pages.

## 🚀 Quick Deploy to GitHub Pages

1. **Create a new repository** named `AceAtDev.github.io` (or use an existing one)

2. **Copy the files** from this `static-site` folder to the root of your repository:
   - `index.html`
   - `style.css`
   - `robots.txt`
   - `sitemap.xml`
   - `images/` folder (add your images here)

3. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Deploy portfolio"
   git push origin main
   ```

4. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `(root)`
   - Click Save

5. Your site will be live at `https://aceatdev.github.io/my-website` 🎉

## 📁 File Structure

```
static-site/
├── index.html      # Main HTML file
├── style.css       # Styles
├── robots.txt      # SEO - search engine crawling rules
├── sitemap.xml     # SEO - sitemap for search engines
├── README.md       # This file
└── images/         # Add your images here
    ├── og-image.jpg      # Open Graph image (1200x630px recommended)
    ├── twitter-image.jpg # Twitter card image (1200x600px recommended)
    └── profile.jpg       # Your profile photo (optional)
```

## 🔍 SEO Features Included

- ✅ Semantic HTML5 structure
- ✅ Meta tags (title, description, keywords)
- ✅ Open Graph tags (Facebook, LinkedIn)
- ✅ Twitter Card tags
- ✅ JSON-LD structured data (Person, WebSite schemas)
- ✅ Canonical URL
- ✅ Robots.txt
- ✅ XML Sitemap
- ✅ Mobile responsive design
- ✅ Accessibility features (ARIA labels, focus states)
- ✅ Fast loading (no external dependencies except fonts)

## 🖼️ Adding Images

For best SEO, add these images to the `images/` folder:

1. **og-image.jpg** (1200x630px) - Shows when shared on Facebook/LinkedIn
2. **twitter-image.jpg** (1200x600px) - Shows when shared on Twitter
3. **profile.jpg** - Your professional photo

## ✏️ Customization

### Update Projects
Edit the `projects-grid` section in `index.html` to add your real projects with:
- Actual project titles
- Real descriptions
- Live project URLs
- Your own screenshots

### Update Content
Search and replace in `index.html`:
- Project titles and descriptions
- Any placeholder URLs

## 📊 After Deployment

1. **Submit to Google Search Console**: https://search.google.com/search-console
2. **Submit sitemap**: `https://aceatdev.github.io/my-website/sitemap.xml`
3. **Test with Lighthouse**: Open DevTools → Lighthouse tab → Generate report

## 📝 License

Personal portfolio - © 2026 Mohamed Elshoubky
