# Personal Theme for revealjs Presentations in Quarto

See a live example [here](https://rawcdn.githack.com/pjkreutzer/pjk_theme_revealjs/92693f422b1d983071fd827f76b9dd9e5258ba7b/template.html)

## Installing


```bash
quarto use template pjkreutzer/pjk_theme_revealjs
```

This will install the extension and create a template for a presentation.

To use the template with an existing presentation use

```bash
quarto install extension pjkreutzer/pjk_theme_revealjs
```

## Using

```yaml
---
title: A title
subtitle: A subtitle
format:
  pjk_theme_revealjs: default
author:
  - name: Jonas Kreutzer
    orcid: 0000-0000-0000-0000
    email: alias@email.com
    affiliations: Your Institution
date: last-modified
---

```
Further extensions can be listed underneath the theme extension.

```bash
format:
  pjk_theme_revealjs:
    attribution: true
```

