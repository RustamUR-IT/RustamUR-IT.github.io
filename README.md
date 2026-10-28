# rustamur-it.github.io

Public website of the app Veilrise: landing page with waitlist (`index.html`), privacy policy, terms, imprint, support and the guild invite page (`join.html`).

## Waitlist
Sign-ups go to Brevo (double opt-in). Paste the form action URL of the Brevo subscription form into `BREVO_URL` at the top of the script in `index.html`. While it is empty, the form opens an email to veilrise.app@gmail.com instead.

Optional: create a contact attribute `SOURCE` (text) in Brevo and add it to the form. Links like `https://rustamur-it.github.io/?s=tiktok` then show where a sign-up came from.

## Assets
`og.png` (link preview, 1200×630), `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`.
