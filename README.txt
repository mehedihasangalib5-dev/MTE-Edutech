MTE website — plain HTML, CSS, JavaScript

Open index.html in a browser. No install or build step.

Files
  index.html                      home page (all sections)
  privacy-policy.html, terms-and-conditions.html, cookie-policy.html, refund-policy.html
  css/style.css                   all styling; colors and fonts are at the top (:root)
  js/main.js                      menu, scroll effects, form (email + optional form-service URL at the top)
  images/                         logo, founder photo, social share image

Before you publish
  1. Replace https://www.example.com with your real domain in every .html file, robots.txt and sitemap.xml
     (search for "example.com").
  2. Contact form: it opens the visitor's email app by default. To send directly from the form,
     create a free form endpoint (e.g. Formspree) and paste its URL into FORM_ENDPOINT in js/main.js.
  3. Legal pages: text lives in legal_content.py style data; to change a policy, edit the matching .html file directly
     (update the "Last Updated" date at the top of the page).
  4. Social links: Facebook and YouTube are set in the footer and team section; edit the href values in the .html files.
  5. Upload the whole folder to any static host (Netlify, GitHub Pages, Cloudflare Pages, cPanel hosting).
