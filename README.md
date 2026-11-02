# Penzam Consultancy website

A static, responsive consultancy website designed for GitHub Pages.

## Publish for free
1. Upload `index.html`, the other `.html` pages, and the `assets` folder to the root of `penzam/penzam.github.io`.
2. Go to repository **Settings → Pages** and set **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
3. Test `https://penzam.github.io` before changing DNS. Do not set the custom domain yet.
4. Once the temporary site works, enter `penzamconsultancy.com` in Settings → Pages → Custom domain, then at GoDaddy configure only the domain's website DNS records for GitHub Pages. Do not change MX, SPF, DKIM or other email-related records. See https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site .
5. Once DNS has propagated, enable **Enforce HTTPS** in GitHub Pages settings.

## Important before publishing
- Confirm or replace the proposed `info@penzamconsultancy.com` email address on `contact.html`.
- Team details and client references have deliberately not been invented.
- The site uses Google Fonts; it falls back to system fonts if blocked.
- The website has no backend, paid service, tracking scripts or contact form.
