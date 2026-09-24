# Turn of War: Endless Crusade Site

[![Build and Deploy](https://github.com/battle-buddy-games/turn-of-war-endless-crusade/actions/workflows/build-deploy.yml/badge.svg)](https://github.com/battle-buddy-games/turn-of-war-endless-crusade/actions/workflows/build-deploy.yml)

This site is generated and managed by the [Battle Buddy Games](https://battle-buddy-games.github.io/Platform/) platform.

## How it works

Content for this site is managed through the platform dashboard. When content is updated, the platform machine rebuilds the site locally, commits the generated `public/` output into this repository, and GitHub Actions deploys that prebuilt output to GitHub Pages.

**Live site:** [https://battle-buddy-games.github.io/turn-of-war-endless-crusade/](https://battle-buddy-games.github.io/turn-of-war-endless-crusade/)

## Local development

To run this site locally:

```bash
# Install Hugo: https://gohugo.io/installation/
hugo server -D
```

The site will be available at `http://localhost:1313/`.

## Structure

```
content/          # Markdown content (managed by platform)
  news/           # News posts
  docs/           # Documentation pages
layouts/          # Hugo templates
static/           # Static assets (CSS, images)
hugo.toml         # Site configuration
```

## Template engine

Built with [Hugo](https://gohugo.io/) -- a fast static site generator.
