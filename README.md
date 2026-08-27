# Formboost HTML Examples

Practical, copy-paste HTML form examples for [Formboost](https://formboost.app/) — a developer-first form backend for websites.

These examples submit directly to:

```text
https://formboost.app/f/YOUR_ENDPOINT
```

## Examples

- [`contact-form.html`](./contact-form.html) — contact form
- [`newsletter-form.html`](./newsletter-form.html) — newsletter signup
- [`feedback-form.html`](./feedback-form.html) — feedback form
- [`survey-form.html`](./survey-form.html) — simple survey

## Getting started

1. Create a form in the [Formboost dashboard](https://dashboard.formboost.app/).
2. Copy your endpoint ID.
3. Replace `YOUR_ENDPOINT` in any example.
4. Open the HTML file in a browser or deploy it to your site.

Example:

```html
<form action="https://formboost.app/f/YOUR_ENDPOINT" method="POST">
  <input name="email" type="email" required />
  <button type="submit">Submit</button>
</form>
```

For advanced configuration, integrations, redirects, spam protection, and API usage, see the [official Formboost documentation](https://formboost.app/docs).

## Links

- [Formboost](https://formboost.app/)
- [Documentation](https://formboost.app/docs)
- [Formboost examples](https://github.com/formboost/formboost-examples)
