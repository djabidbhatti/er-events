# ER Events — Luxury Event Website

A responsive, single-page website for **ER Events**, styled to complement the supplied crowned gold-and-charcoal logo.

## Files

- `index.html` — complete homepage with the Formspree enquiry form.
- `thankyou.html` — branded confirmation page with the submitted enquiry summary and email/WhatsApp actions.
- `logo.png` — your supplied ER Events logo.
- `README.md` — setup and publishing instructions.

## Preview locally

Keep `index.html` and `logo.png` in the same folder, then open `index.html` in a modern browser. An internet connection is needed for the web fonts and remote gallery photographs.

## Before publishing

1. Open `index.html`.
2. The business email is configured as `djabidbhatti@gmail.com`.
3. If your contact email changes later, update the `BUSINESS_EMAIL` constant in `index.html`.
4. Review the wording and event services to ensure they accurately represent your business.
5. The sample gallery uses remote Unsplash image URLs. Replace them with your own event photos when available.

**Contact form note:** The form submits to Formspree at `https://formspree.io/f/moejyogw`. After a successful submission, the visitor is redirected to `thankyou.html`. The thank-you page includes the ER Events logo and matching black-and-gold styling, displays the submitted details, and provides buttons to prepare the same enquiry for `djabidbhatti@gmail.com` or WhatsApp `+92 321 5333732`. Visitors must press Send in the email or WhatsApp app to send a separate copy. Make sure Formspree email notifications are configured to deliver submissions to your intended inbox.

## Publish with GitHub Pages

Repository: https://github.com/djabidbhatti/er-events

1. Download or extract the website files.
2. Open your repository on GitHub and upload `index.html`, `thankyou.html`, `logo.png`, and `README.md` to the repository's top level.
3. Commit the files to your default branch (usually `main`).
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**, select your default branch and the `/ (root)` folder, then save.
6. Once deployment completes, use the site URL shown in Settings → Pages.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## WhatsApp

The form has two buttons. **Submit Enquiry** sends the enquiry to Formspree (email) and then opens `thankyou.html`, where the main button opens WhatsApp with the enquiry pre-written. **Send on WhatsApp** skips Formspree and opens WhatsApp directly with the message ready. In both cases the customer must press Send in WhatsApp. Fully automatic delivery to WhatsApp needs a paid WhatsApp Business API / automation service.

## Customisation

- Colours are defined at the top of the `<style>` block as CSS variables.
- Edit the service cards and gallery captions directly in `index.html`.
- The business email is set to `djabidbhatti@gmail.com`; update it in both HTML files if it changes.
- The Formspree endpoint is set to `https://formspree.io/f/moejyogw`.
- Add your real phone number, social links, service area, and business details as needed.

## License and imagery

The supplied logo is included for this project. Gallery photographs load from Unsplash URLs; verify the terms for any images you choose to keep in a commercial deployment. Replace sample imagery with photos you own or are licensed to use.
