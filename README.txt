ARBOR COMPUTERS - REDESIGNED HOMEPAGE (static site)

FILES
  index.html   Five-page site (home, dental-it, business-it, repair, contact) (HTML, CSS, JS in one file, no build step)
  robots.txt   Search engine rules
  sitemap.xml  Sitemap (add new pages as you build them)

DEPLOY
  Any static host works (cPanel/FTP, Netlify, Cloudflare Pages, Vercel, GitHub Pages).
  1. Upload all three files to the site root (public_html or equivalent).
  2. Visit the site on desktop and phone and check every section.
  3. WordPress sites: take a backup first. Upload via FTP or use a
     "custom page template"/static page plugin. Do not overwrite the WP index.

BEFORE GOING LIVE
  - CONTACT FORM IS A DEMO. It validates but does not send. Connect it to
    email or a form service (Formspree, Netlify Forms, Web3Forms, or the
    current Arbor contact form) by setting the form's action and method.
  - Confirm "walk in, no appointment" is current policy (it comes from a
    customer review) and add business hours.
  - Add real photos (team, shop, offices). None are included.
  - Add Google Analytics / Search Console verification if used.
  - Confirm the Google Maps link and Remote Support link still work.
  - Fonts load from Google Fonts. Self-host them if privacy rules require.

NOTES
  - Local business schema (JSON-LD), canonical and Open Graph tags are included.
  - Add a 1200x630 og:image once a brand image exists.
  - Other pages (About, Dental IT, specialties, Blog) are not in this package.
