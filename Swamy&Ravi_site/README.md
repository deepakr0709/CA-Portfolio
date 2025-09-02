
Swamy & Ravi — Static Multi-page Website (vksaiyer.com inspired structure)
-------------------------------------------------------------------------------

What's inside:
- index.html (home)
- about.html (about)
- services.html (services)
- team.html (team)
- contact.html (contact)
- css/style.css (styles)
- js/main.js (smooth scroll)
- assets/ (empty - images are hotlinked from Unsplash)

How it's different from the original:
- New modern color palette (deep-navy + purple + teal)
- Different layout, fonts and imagery (Unsplash links). Content is paraphrased and not copied.
- Multi-page static HTML for easy hosting anywhere.

How to run locally:
- Unzip the project and open index.html in your browser.
- Or serve via a local static server e.g.:
  python3 -m http.server 8000
  open http://localhost:8000

Deploy options:
- Netlify or Vercel: Create a new site and upload the folder or connect a GitHub repo.
- GitHub Pages: Use gh-pages branch or repo settings to publish.

Contact form note:
- The included form uses a mailto fallback. For production, consider:
  - Netlify Forms (if hosting on Netlify)
  - Formspree or Basin (serverless form endpoints)
  - A small backend (Spring Boot/Express) to accept form POSTs

Images & credits:
- Photos are hotlinked from Unsplash (free to use). Replace hotlinks with local images in assets/ if you want the zip to be fully offline.

Domain purchase & DNS (brief):
1) Buy domain from Namecheap/GoDaddy/Google Domains.
2) In your hosting dashboard (Netlify/Vercel), add the domain and follow their DNS instructions.
3) Update domain's nameservers or add A/CNAME records as provided by your host.
4) SSL is provisioned automatically by Netlify/Vercel.

If you'd like, I can:
- Replace hotlinked images with downloaded images included in the zip (requires larger zip).
- Wire the contact form to Netlify Forms or provide a small Spring Boot endpoint.
- Push this project to a GitHub repo and set up a one-click deploy to Netlify/Vercel.
