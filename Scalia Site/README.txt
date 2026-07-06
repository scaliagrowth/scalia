Scalia — Netlify deploy bundle
==============================

Drop the contents of this folder into your Netlify site root
(or push to the connected repo at the project root).

Files:
  index.html     — landing page (scaliagrowth.com/)
  privacy.html   — served at /privacy via _redirects
  terms.html     — served at /terms via _redirects
  _redirects     — Netlify clean-URL rules (200 rewrites)
  robots.txt     — allow all crawlers + sitemap pointer
  sitemap.xml    — 3 URLs for search engines
  favicon.svg    — gradient S mark

After deploy, verify:
  https://scaliagrowth.com/
  https://scaliagrowth.com/privacy
  https://scaliagrowth.com/terms
