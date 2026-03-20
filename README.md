# pjk_theme

A personal Quarto theme for HTML documents and RevealJS presentations.

## Installing

To start a new project from the template:

```bash
quarto use template pjkreutzer/pjk_theme
```

To add the theme to an existing project:

```bash
quarto install extension pjkreutzer/pjk_theme
```

## Usage

The extension provides two formats:

| Format | Use with |
|---|---|
| `pjk_theme-html` | HTML documents |
| `pjk_theme-revealjs` | RevealJS presentations |

### HTML Document

```yaml
---
title: A title
format:
  pjk_theme-html: default
author: Jonas Kreutzer
date: last-modified
---
```

### RevealJS Presentation

```yaml
---
title: A title
format:
  pjk_theme-revealjs: default
author: Jonas Kreutzer
date: last-modified
---
```

Both formats accept additional options under the format key:

```yaml
format:
  pjk_theme-html:
    toc: true
```

```yaml
format:
  pjk_theme-revealjs:
    center: true
```

