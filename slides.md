---
title: InvenTree 37c3 Lightning Talk
# theme: night
revealOptions:
  transition: 'fade'
---

# InvenTree - 37c3 Lightning Talk

---

# The Problem

CC by SA Image of boxes

Created for 37c3 lightning talks

---

# The logical solution: Inventory Management

Inventory management software
- Part mamagment
- Parameters (resistance, voltage, package, ...)
- Stock tracking
and more

---

# Who am I? mjmair.com

Matthias Mair @matmair
- I work in civil engineering + something with IT
- Proud Austrian (no kangaroos)
- Involved with InvenTree since 2021 (±2k commits)

---

# InvenTree Project  inventree.org

MIT licensed, Python/Django based, since 2017

Developed by a stable core team of volunteers (3-5)

75+ contributors, 3k+ stars

50+ translators for 30+ languages (8 are +75%)

# Architecture

Server-Client architecture
- Central API service - REST + OpenAPI spec (Django)
- Web frontend (HTML + vanilla JS / React)
- Android / iOS app (Flutter)
- Python API client

---

# Business Logic

Core models: Part, Stock, Order (sales purchase), Build

Models can be extended with strongly typed parameters (SI) or JSON OOB

Support for deep plugin integration (custom UI, API, models, ...)

---

# Enterprise ready

Security: SSO, LDAP, MFA, RBAC, 12 factor app, ...

Deployment: Debian / Ubuntu, Docker, DigitalOcean, ...

Best Practices: OpenSSF passing, ±90% coverage, CI/CD, SAST, enforced code style, ...


---

# Ecosystem highlights

- InvenTree Plugins: Shopify, Mouser, PCBA, loan management
- Label Printers: Brother, Zebra, CUPs
- Notifications: Email, Slack, Apprise
- Native KiCad database integration (nightly / 8)
- CLI / import tools for various vendors

---

# We need you! inventree.org

Bug reporters / testing development versions

Translators and proofreaders

Documentation writers

Developers (Python, JS/TS, Flutter, ...)

Feature Funding / long term sponsors

---

Extra slides

---

# Outlook

- New frontend - Graduating to 1.0
- MES / Production planning
- File / Project management
- Integration with the (F)OSS/OSHW ecosystem
