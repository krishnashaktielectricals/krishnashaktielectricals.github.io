# Krishna Shakti Electricals website

Static site for GitHub Pages. No build step.

## Before launch

Search `index.html` for `TODO` and fill each one:

1. Closing time and weekly off day (page and JSON-LD comment).
2. Product groups and brands.
3. Google review link from the GBP "Ask for reviews" button.
4. Official map embed from Google Maps > Share > Embed a map.
5. WhatsApp number.
6. Domain. The site uses `krishnashaktielectricals.github.io`. After buying a domain, replace it in `index.html`, `robots.txt` and `sitemap.xml`.

## GitHub Pages setup

1. Sign up at github.com with the owner's Gmail. Username: `krishnashaktielectricals`.
2. Create a public repo named `krishnashaktielectricals.github.io`.
3. Upload every file in this folder to the repo root.
4. Settings > Pages > Source: Deploy from a branch, `main`, `/ (root)`.
5. Settings > Collaborators: add the developer's GitHub account.

## Custom domain

1. Buy the domain. Add a file named `CNAME` with one line: `krishnashaktielectricals.in`.
2. At the registrar, add four A records for `@`:
   `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
3. Add a CNAME record: `www` to `krishnashaktielectricals.github.io`.
4. Settings > Pages: enter the domain, wait for the DNS check, tick "Enforce HTTPS".

## After launch

1. GBP > Edit profile > Website: `https://krishnashaktielectricals.in/?utm_source=gbp&utm_medium=organic`.
2. Google Search Console: add a Domain property, verify with the DNS TXT record, submit `sitemap.xml`.
3. Test the schema at https://search.google.com/test/rich-results.
