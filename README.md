# Personal Google Workspace OAuth site

Static site backing the OAuth consent-screen configuration for a personal,
single-user Google Cloud project.

- `index.html`     — application homepage (app info / what the integration accesses)
- `privacy.html`   — privacy policy

## Publish

Push to GitHub Pages: repo Settings -> Pages -> Source: Deploy from a branch,
branch `main`, folder `/ (root)`. The site lands at
`https://<user>.github.io/hermes-oauth-site/`.

## Notes

- The project is deliberately NOT submitted for OAuth verification, so Google
  never validates this domain. Neither page is reviewed by anyone.
- Because the app is unverified, the consent screen shows a generic app name,
  not a branded one. Do not be alarmed by that at sign-in.
- `privacy.html` should keep its duplicate `gmail.send` line trimmed once you
  settle on final scope wording.
