# ASANTESONGGLOBAL (ASGLOBE)

Corporate website for **ASANTESONG GLOBAL PROCUREMENT, TRADE & LOGISTICS LIMITED**, a Ghanaian procurement, trading and logistics coordination company.

**Global Sourcing. Trusted Supply. Seamless Logistics.**

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000> in a browser.

## Publish with GitHub Pages

GitHub Pages is configured to publish the repository root from the `main` branch at <https://asantesongglobal.com/>. Pushing changes to `main` publishes them automatically.

The general contact, quote, and supplier forms all use the same Formspree endpoint and work with GitHub Pages. The quote and supplier forms do not include file uploads because the Formspree free plan does not include upload storage.

## Form setup

All three forms post to the Formspree endpoint configured in their respective HTML pages. To change the destination mailbox or review submissions, manage the form in the Formspree dashboard associated with that endpoint. Formspree requires the recipient email to be verified.

## Pages

- Home: `index.html`
- About ASANTESONGGLOBAL: `about.html`
- Services: `service.html`
- Industries: `industries.html`
- Products: `products.html`
- Request a quote: `quote.html`
- Supplier enquiries: `supplier.html`
- Contact: `contact.html`

Buyer and supplier form submissions are handled by Formspree.
