---
title: InvenTree 37c3 Lightning Talk
# theme: night
revealOptions:
  transition: 'fade'
  center: false
---

# InvenTree - 37c3 Lightning Talk

---

# Problem: Chaos

TODO: CC by SA Image of boxes

Created for 37c3 lightning talks

---

# Solution: Inventory Management

InvenTree Inventory management software
- Part mamagment
- Parameters (resistance, voltage, package, ...)
- Stock tracking
and more

---

# Who am I?

Matthias Mair @matmair
- I work in civil engineering / IT
- Austrian (no kangaroos)
- Involved with InvenTree since 2021 (±2k commits)

mjmair.com

---

# InvenTree Project

MIT licensed, Python/Django based, since 2017

Developed by a stable core team of volunteers (3-5)  
75+ contributors, 3k+ stars on GitHub  
50+ translators for 30+ languages (8 are +75%)

inventree.org

---

# Architecture

Server-Client architecture
- Central API service - REST + OpenAPI spec (Django)
- Web frontend (HTML + vanilla JS / React)
- Android / iOS app (Flutter)
- Python API client

---

# Business Logic

Core business objects:
- Part, Stock
- Order (sales, purchase, return)
- Build

Models can be extended:
- strongly typed (incl. SI conversion support) *parameters*
- loosly typed JSON *metadata*

Plugins for: custom UI, API, models, ...

---

# Enterprise ready

Security: SSO, LDAP, MFA, RBAC, 12 factor app, ...

Deployment: Debian / Ubuntu, Docker, DigitalOcean, ...

Best Practices: OpenSSF badge: passing, ±90% coverage, CI/CD, SAST, enforced code style, ...


---

# Ecosystem highlights

- InvenTree Plugins: Shopify, Mouser, PCBA, loan management
- Label Printers: Brother, Zebra, CUPs
- Notifications: Email, Slack, Apprise
- Native KiCad database integration (nightly / 8)
- CLI / import tools for various vendors

---

# We need you! invenTree.org/

We are always looking for people:
- reporting bugs / testing development versions
- translating and proofreading
- writing documentation
- developing (Python, JS/TS, Flutter, ...)
- funding features / sponsoring long term
- communicating about the project, answersing quetions, ...

You do not need to be a "developer" to contribute! visit inventree.org/contribute

---

Extra slides

---

# Outlook

- New frontend - Graduating to 1.0
- MES / Production planning
- File / Project management
- Integration with the (F)OSS/OSHW ecosystem
