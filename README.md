# Blessed Hands by Rafi

Static one-page site. No build step: open `index.html`, or run `python3 -m http.server`.

- Booking link: search `book.squareup.com` in `index.html` (3 buttons).
- Photos: `assets/`. Swap files in place, keep the names.
- Before launch: replace `YOUR-DOMAIN.com` in the `og:image` tag.

## Deploy (Cloudflare Pages)
1. Push this folder to a GitHub repo.
2. Cloudflare dashboard > Workers & Pages > Create > Pages > Connect to Git.
3. Build command: none. Output directory: `/`.
4. Custom domains > add the domain (buy it at Cloudflare Registrar first).
