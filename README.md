<div align="center">

# 🎨 No-code Theming for Open edX with Design Tokens

### Rebrand the whole platform from the admin panel, without touching code

**Product owner:** [TitanEd](https://github.com/TitanEd) &nbsp;·&nbsp; **My role:** Frontend Engineer (design-token system and theme builder) &nbsp;·&nbsp; **Aug 2026 – Oct 2026**

![Design Tokens](https://img.shields.io/badge/Design%20Tokens-7B61FF?style=flat)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Open edX](https://img.shields.io/badge/Open%20edX-02262B?style=flat)

</div>

> **Note:** the source code is private to TitanEd. This repository is a **project showcase** and contains no company code.

---

## 📌 The business problem

Every customer wants the platform in **their own brand**. On standard Open edX, changing the look means a developer editing
styles across **11 separate apps**, then a rebuild and a deploy. It's slow and expensive for every client, and it can break things.

## ✅ What I delivered

A **design-token theming system with a theme builder**. Admins change the entire look of the platform **from the admin panel,
without touching code**:

| An admin can change | Where it applies |
|---|---|
| 🎨 Colours (primary, secondary, backgrounds, states) | Every Open edX app: LMS, Studio, login, dashboards, public pages |
| 🔤 Font family and font sizes | Headings, body text, buttons, navigation |
| 📐 Spacing, widths, corner radius | Layout and components |
| 🧩 Every component's style | Buttons, links, cards, headers, dropdowns, forms |
| ✨ A completely new theme | Built from the ready-made templates |

**Ready-made brand templates:** *Native*, *Template A* and *Template B*. A new customer starts from a template and adjusts it.

**Works everywhere:** used in [TELS](https://github.com/sonukumarsingh01/tels-saas-learning-platform), TitanEd's SaaS platform,
**and** on any standard Open edX installation.

## 📈 Business impact

- **A new client brand takes minutes of configuration**, not days of development.
- **No risk:** branding changes never touch application code.
- **One system for all customers**, which lowers the cost of every new client.

## 🏗️ How it's built

```
  Admin panel (theme builder)
          │  token values (colours, fonts, sizes…)
          ▼
  Base tokens ──► Component tokens ──► 11 Open edX apps
  (colour, type,   (button, link, card,   (LMS, Studio, login,
   spacing)         header, dropdown)       dashboards, public)
```

**Tech:** Paragon design tokens (the Open edX design system), SCSS, React, Tutor plugins.

---

<div align="center">

**Sonu Kumar** · Frontend Engineer · [LinkedIn](https://www.linkedin.com/in/dr-sonu-kumar/) · [GitHub](https://github.com/sonukumarsingh01)

</div>
