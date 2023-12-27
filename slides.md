---
title: InvenTree 37c3 Lightning Talk
# theme: night
revealOptions:
  transition: 'fade'
  center: false
---

# InvenTree - 37c3 Lightning Talk

---

# Problem: Loose Box Chaos

![Loose Box Chaos](assets/loose-box-chaos.jpg)


Photo by <a href="https://unsplash.com/de/@purzlbaum">Claudio Schwarz</a> on <a href="https://unsplash.com/de/fotos/braune-kartons-auf-schwarzer-plastikkiste-q8kR_ie6WnI">Unsplash</a>
  

---

# Solution: Inventory Management

**InvenTree**: Inventory management software
- Part mamagment
- Parameters (resistance, voltage, package, ...)
- Stock tracking
and more

[inventree.org](https://inventree.org)

---

# Who am I?

Matthias Mair / @matmair
- I work in civil engineering / IT
- Austrian (no kangaroos)
- Involved with InvenTree since 2021 (±2k commits)

[mjmair.com](https://mjmair.com)

---

# InvenTree Project

MIT licensed, Python/Django based, started 2017

Developed by a core team of volunteers (3-5)  
75+ contributors, 3k+ stars on GitHub  
50+ translators for 30+ languages (8 are +75% proofred)

[inventree.org](https://inventree.org)

---

# Components

Server-Client architecture
- Central API service - REST + OpenAPI spec (Django)
- Web frontend (HTML + vanilla JS / React)
- Android / iOS app (Flutter)
- Python API client

---

# Business Logic

Core business objects:
- Part, Stocklocation, Stock (1:n:n)
- Order (sales, purchase, return)
- Build

Models can be extended:
- strongly typed *parameters*  
  SI conversion support
- loosly typed JSON *metadata*

Plugins to extend and customize

---

# Enterprise ready

Security: SSO, LDAP, MFA, RBAC, 12 factor app, ...

Deployment: Debian / Ubuntu packages, Docker image, install script, DigitalOcean, ...

Best Practices: OpenSSF best practices, ±90% coverage, CI/CD, SAST, enforced code style, ...

Open for feedback


---

# Ecosystem highlights

- InvenTree Plugins: Shopify, Mouser, PCBA, loan management
- Label Printers: Brother, Zebra, CUPs
- Notifications: Email, Slack, Apprise
- KiCad database integration (nightly / 8)
- CLI / import tools for various vendors

---

# We need you! InvenTree.org

We are always looking for people:
- reporting bugs / testing development versions
- translating and proofreading
- writing documentation / guides
- developing (Python, JS/TS, Flutter, ...)
- funding features / sponsoring long term
- communicating about the project, answersing quetions, ...

You do not need to be a "developer" to contribute!  visit [inventree.org/contribute](https://inventree.org/contribute)

---

# Friendly projects in the space

- Part-DB: inventory management in PHP [Part-DB/Part-DB-server](https://github.com/Part-DB/Part-DB-server)
- kitspace.org: OSHW project repo [kitspace/kitspace](https://github.com/kitspace/kitspace)

---

# Contact

Projekt: inventree.org

Me: mjmair.com / @matmair on GitHub

Slides and more: 37c3.mjmair.com

---

Extra slides

---

# Outlook

- New frontend - Graduating to 1.0
- MES / Production planning
- File / Project management
- Integration with the (F)OSS/OSHW ecosystem
