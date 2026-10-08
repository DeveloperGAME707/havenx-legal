# HAVENX Legal Pages (GitHub Pages)

This folder contains a small static website with:
- `index.html` — legal landing page
- `terms.html` — Terms of Service
- `privacy.html` — Privacy Policy
- `.nojekyll` — prevents Jekyll processing

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `havenx-legal`.
2. Upload all files in this folder to the repository root (not the containing folder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for GitHub Pages to publish, then open **Visit site**.

If your GitHub account name is `DeveloperGAME707`, the expected URLs after successful publication are:
- Home: `https://developergame707.github.io/havenx-legal/`
- Terms of Service URL: `https://developergame707.github.io/havenx-legal/terms.html`
- Privacy Policy URL: `https://developergame707.github.io/havenx-legal/privacy.html`

These URLs are only live once you create the repository and enable Pages. If your GitHub username is different, replace `developergame707` with your actual username.

## Discord Developer Portal

Open your application's **General Information** page and fill:
- **Terms of Service URL** with the published `/terms.html` URL.
- **Privacy Policy URL** with the published `/privacy.html` URL.

The page is public. Do not upload Discord bot tokens, `.env`, Firebase service-account JSON, or other private credentials to this repository.

## Please review before publishing

This is a practical starter template, not legal advice. Please confirm that the data practices described here match the current deployed bot and client. Update the contact details or add a business/legal address if you have one and want to publish it.
