# Known Limitations

This is an honest preview of the paid MVP package. The goal is buyer trust, not exaggerated claims.

## MVP Scope

- The paid package is an MVP codebase, not a finished production SaaS.
- Production deployment must be validated by the buyer on their chosen infrastructure.
- Production secrets, domains, hosting, storage, email, analytics, and payment accounts are not included.
- Legal pages, privacy policies, terms, compliance review, and production support processes are buyer responsibilities.

## Product Limitations

- Payment and subscription billing are not included by default.
- OAuth requires buyer-owned provider credentials and callback configuration.
- AI provider behavior depends on the buyer's API key, model, billing status, base URL, and provider compatibility.
- OpenAI-compatible providers can have edge cases and should be tested with the exact provider/model before demos.
- Production monitoring, admin tools, analytics, rate-plan limits, and customer-support workflows may need additional work.

## Technical Limitations

- Internal package names may retain legacy workspace naming in the private codebase.
- A full internal namespace rename is intentionally avoided in the MVP package to reduce risk.
- Non-English locale files may need a full buyer-side copy review if multilingual launch matters.
- Local development credentials are demo defaults and must not be reused in production.
- Public production use requires additional review of backups, security headers, CORS, rate limits, SSRF controls, logging, and secret rotation.

## Showcase Limitations

- This public repo does not include private source code.
- Screenshots are placeholders until replaced with real product captures.
- Demo video link is a placeholder until the seller uploads the final walkthrough.
- Gumroad purchase link is a placeholder until the listing is live.
