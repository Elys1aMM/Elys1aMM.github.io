# Yox1no.github.io

Personal website and blog built with [Hugo](https://gohugo.io/) and the [Stack](https://github.com/CaiJimmy/hugo-theme-stack) theme, automatically deployed via GitHub Actions to [yox1no.github.io](https://yox1no.github.io/).

## Overview

This repository hosts source files for technical notes, paper reading notes, and project logs.

## Structure

```text
.
├── .github/workflows/   # GitHub Actions build & deployment pipeline
├── archetypes/          # Hugo content templates
├── assets/              # Stylesheets and processed assets
├── config/_default/     # Hugo & Stack theme configuration
├── content/             # Blog posts and pages
├── i18n/                # Localization overrides
├── layouts/             # Custom layout partials
├── static/              # Static assets (images, favicon)
└── themes/              # Stack theme submodule
```

## Local Development

Requires **Hugo Extended** (`v0.120+`).

```bash
git clone --recursive https://github.com/Yox1no/Yox1no.github.io.git
cd Yox1no.github.io
hugo server -D
```
