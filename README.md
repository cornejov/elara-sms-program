# Elara SMS program pages

Public A2P 10DLC program pages for private, two-way Elara SMS. No secrets, phone numbers, or legal names belong in this repository.

- [Program home](index.html)
- [Consent / opt-in](consent.html)
- [Privacy](privacy.html)
- [Terms](terms.html)

Hosted: `https://cornejov.github.io/elara-sms-program/`

`consent.html` must not be published as operational until its
`elara-consent-endpoint` meta value is the stable public HTTPS tunnel URL for
`POST /api/v1/sms/consent`. The endpoint persists the receipt before returning
success; an empty endpoint keeps submission disabled.
