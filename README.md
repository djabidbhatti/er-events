# ER Events — Luxury Event Website

A responsive, single-page website for **ER Events**, styled to complement the supplied crowned gold-and-charcoal logo.

## Files

- `index.html` — complete website (HTML, CSS, and JavaScript are included in one file).
- `logo.png` — your supplied ER Events logo.
- `index-code.txt` — a plain-text copy of the complete HTML source.
- `README.md` — setup and publishing instructions.

## Preview locally

Keep `index.html` and `logo.png` in the same folder, then open `index.html` in a modern browser. An internet connection is needed for the web fonts and remote gallery photographs.

## Before publishing

1. Open `index.html`.
2. The business email is configured as `djabidbhatti@gmail.com`.
3. If your contact email changes later, update the `BUSINESS_EMAIL` constant in `index.html`.
4. Review the wording and event services to ensure they accurately represent your business.
5. The sample gallery uses remote Unsplash image URLs. Replace them with your own event photos when available.

**Contact form note:** This is a static GitHub Pages website. The enquiry form opens the visitor's email application; it does not send or store submissions on a server.

## Publish with GitHub Pages

Repository: https://github.com/djabidbhatti/er-events

1. Download or extract the website files.
2. Open your repository on GitHub and upload `index.html`, `logo.png`, and `README.md` to the repository's top level. You may also upload `index-code.txt` for reference.
3. Commit the files to your default branch (usually `main`).
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**, select your default branch and the `/ (root)` folder, then save.
6. Once deployment completes, use the site URL shown in Settings → Pages.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Customisation

- Colours are defined at the top of the `<style>` block as CSS variables.
- Edit the service cards and gallery captions directly in `index.html`.
- Replace the placeholder business email in the JavaScript before using the enquiry form.
- Add your real phone number, social links, service area, and business details as needed.

## License and imagery

The supplied logo is included for this project. Gallery photographs load from Unsplash URLs; verify the terms for any images you choose to keep in a commercial deployment. Replace sample imagery with photos you own or are licensed to use.
