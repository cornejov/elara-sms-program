# Elara SMS program pages

Public A2P 10DLC program pages for private, two-way Elara SMS. No secrets, phone numbers, or legal names belong in this repository.

- [Program home](index.html)
- [Consent / opt-in](consent.html)
- [Privacy](privacy.html)
- [Terms](terms.html)
- Hosted sample-form screenshot: [review/opt-in-sample.png](review/opt-in-sample.png)

Hosted: `https://cornejov.github.io/elara-sms-program/`

`consent.html` has two modes:

- **No invitation (public / carrier review):** shows a labeled sample of the same opt-in form. Submit does not record production consent and does not send SMS.
- **Private one-use invitation:** live consent POST to `elara-consent-endpoint`. Success only after the server persists the receipt. This page still does not send SMS.
