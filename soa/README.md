# IBM Certified SOA Associate [2008] - hosted Open Badge

## Setup (one time)

1. Put the 4 files in this folder at the path `soa/` in the root of the
   `certificates` repo (branch `main`).
2. Enable GitHub Pages: repo Settings -> Pages -> Source: "Deploy from a branch",
   Branch: `main`, folder `/ (root)`. Save.
3. Wait ~2 minutes, then confirm this URL returns JSON in your browser:
   https://souzacarvalh.github.io/certificates/soa/assertion.json

## Import to Credly

Upload `ibm-certified-soa-associate.png` (this baked copy, not an older one).
Credly will fetch assertion.json -> badge.json -> issuer.json and verification
should pass. The recipient email baked in is souzacarvalh@gmail.com - it must
match your Credly account email (or add it as a secondary email in Credly).
