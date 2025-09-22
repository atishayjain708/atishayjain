# Atishay Jain personal site

Static, Netlify-ready replica of https://atishayjain.carrd.co/ with improved SEO and adjustable hero photo.

## Deploy on Netlify
1) Create a new site on Netlify and drag-drop this folder, or connect a Git repo with these files.
2) Set your custom domain in Netlify. Enable HTTPS.
3) Replace `YOUR-DOMAIN.com` in:
   - index.html canonical and og:image
   - robots.txt
   - sitemap.xml
4) Submit the domain in Google Search Console and request indexing for the homepage.

No build step required. Pure static HTML and CSS.

## Set your hero photo via Google Drive
- Replace the placeholder at `/assets/profile-placeholder.png` OR pass a public URL as a query param:
  - Example: `https://YOUR-DOMAIN.com/?photo=https://drive.google.com/uc?export=view&id=FILE_ID`
- Adjust the size of the circular frame by editing `--profile-size` in `assets/styles.css`.

## Updated links
- Hyperke Website: https://hyperke.com
- Eagle Info Services: https://eagleinfoservices.com
- LinkedIn: https://linkedin.com/in/atishay-hyperke
- YouTube: https://www.youtube.com/@atishay-jain-hyperke
