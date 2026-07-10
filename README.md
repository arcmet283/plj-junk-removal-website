# PLJ Junk Removal & Delivery — Website

Marketing site for PLJ Junk Removal & Delivery/Pickup, serving Aiken, SC and the surrounding area.

Call: 803-226-3830

## Hosting

Deployed via GitHub Pages from the `main` branch.

## Notes

- The customer reviews and social media links (Facebook/Instagram/Google) are placeholders and should be swapped for real content before final launch.
- The "Get a Free Quote" online form (in the `#quote` section) is built but not yet wired up to receive submissions. To activate it:
  1. Sign up for a free account at [formspree.io](https://formspree.io) using the business email (e.g. info@pljjunkremoval.com).
  2. Create a new form in the Formspree dashboard — it will give you a form endpoint like `https://formspree.io/f/abcd1234`.
  3. In `index.html`, find `action="https://formspree.io/f/YOUR_FORM_ID"` and replace `YOUR_FORM_ID` with your real form ID.
  4. Commit and push. Formspree sends a confirmation email on the first real submission — click the link in that email to activate the form.
  - Until this is done, the form shows a friendly message directing visitors to call instead of silently failing.
