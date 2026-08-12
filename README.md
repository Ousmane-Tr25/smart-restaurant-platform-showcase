<div align="center">
  <img src="assets/logo-smart-restaurant.svg" width="112" alt="Smart Restaurant Platform logo">

# Smart Restaurant Platform — Public Showcase

**International white-label restaurant ordering and operations platform.**

`FastAPI` · `PostgreSQL` · `Alembic` · `Docker` · `PWA` · `5 public languages` · `v2.1.1 stable`

[Product website](https://ousmane-tr25.github.io/smart-restaurant-platform-showcase/) · [Mali demo](https://bamako-delices-demo.onrender.com/menu?v=211) · [Russia demo](https://smart-restaurant-ru-test.onrender.com/menu?v=211) · [Author profile](https://github.com/Ousmane-Tr25)
</div>

> This repository is a public product showcase. The commercial application source is maintained separately and is not distributed here.

## Product status

- **Stable web release:** v2.1.1
- **216 automated tests passed**
- **85 Jinja templates compiled**
- **Language audit:** PASS
- **Final QA:** PASS
- **Official release gate:** PASSED

## What the platform covers

### Customer experience

- Public menu and configurable guest checkout.
- OTP-secured customer account for personal orders, reservations, loyalty, reviews and support.
- Item options, supplements, spice levels, favorites and order tracking.
- Installable PWA with responsive desktop and mobile experiences.
- Bambara, French, Russian, English and Chinese public interfaces.

### Restaurant operations

- Owner, administrator, manager, cashier, kitchen, delivery and support workspaces.
- Orders, kitchen workflow, payments, receipts, reservations, tables and QR menus.
- Stock, ingredients, recipes, suppliers, expenses, costs and margin reporting.
- Privacy requests, encrypted backups, Web Push and transactional notification outbox.

### White-label Design Studio

- Colors, typography, cards, buttons, fields, corners, borders and shadows.
- Image ratios, `cover/contain`, focal position, zoom and alternative text.
- Configurable carousel for “Need anything else?” recommendations.
- Public-menu/account policy controlled separately by OWNER/ADMIN.

## Public demonstrations

### Mali — Bamako Délices

- Currency: XOF / FCFA
- Brevo email OTP: functional
- Web Push VAPID: functional
- Pay at restaurant / on delivery: available
- PayDunya: temporarily disabled pending external sandbox confirmation

[Open Mali demo](https://bamako-delices-demo.onrender.com/menu?v=211)

### Russia — Smart Restaurant RU Test

- Currency: RUB
- YooKassa sandbox: validated
- Card/YooMoney test checkout: validated
- Server-side webhooks and partial/full refund scenarios: validated
- **No real money is used in the test environment**

[Open Russia demo](https://smart-restaurant-ru-test.onrender.com/menu?v=211)

## Analytics

The current release includes descriptive business analytics and decision support:

- revenue, average basket, expenses and margins;
- best-selling products, quantities and product revenue;
- customer history, loyalty and reviews;
- operational reports and CSV exports;
- explainable rule-based recommendations.

Predictive machine learning is a future data-science project, not a claim of v2.1.1.

## Integration status

| Integration | Status |
|---|---|
| Brevo email OTP | Functional |
| Web Push VAPID | Functional, subscription material encrypted at rest |
| YooKassa | Sandbox validated |
| PayDunya | Connector retained, temporarily disabled |
| Stripe | Connector available, not active in current demos |
| Pay at restaurant / delivery | Available |

## Security and privacy

The product includes server-side payment verification, idempotent webhooks, CSRF/origin protections, hardened headers, session revocation, encrypted Web Push subscription material, customer export/anonymization workflows and encrypted backup support.

This public repository contains **no** provider secrets, customer records, database backups, environment files or commercial source code.

## Native roadmap

The next separate product phase is a native iOS/Android customer application. The stable web platform remains the authoritative backend and administration layer.

## Repository contents

```text
index.html / fr.html        bilingual public website
styles.css / script.js      responsive and accessible presentation
assets/screenshots/         anonymized current product visuals
PROJECT_FACTS.md            verifiable release facts
KNOWN_LIMITATIONS.md        transparent current limits
SECURITY.md                 showcase security policy
```

## Author

**Ousmane Traoré** — Python, Data and ML-oriented developer building practical production-structured applications.

GitHub: [Ousmane-Tr25](https://github.com/Ousmane-Tr25)

## License

Copyright © 2026 Ousmane Traoré. All rights reserved. This showcase and its visual assets may not be reused commercially without written authorization.
