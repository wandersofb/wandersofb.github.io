## About

This repository hosts my résumé site, built with Jekyll on top of `sproogen/resume-theme` and deployed through GitHub Pages. All profile information, education, and experience entries are configured centrally in `_config.yml` for easy maintenance.

## Quick Start

1. Install dependencies: `bundle install`
2. Run the local preview server: `bundle exec jekyll serve`
3. Open the address printed in the terminal (default `http://127.0.0.1:4000`) to see live updates.

## Customization

- **Site details**: Update `name`, `title`, `about_content`, and social links inside `_config.yml`.
- **Content sections**: Still in `_config.yml`, edit the `content` array to maintain education, experience, and other sections (supports Markdown line breaks).
- **Styles/layouts**: Override theme styles in `_sass`, and extend structure through `_includes` or `_layouts`.
- **Assets**: Store images and other static resources inside `assets` or `images` and reference them from Markdown.

## Deployment

Pushing to the `main` branch triggers GitHub Pages to build and publish the site automatically. To test a production build locally, run `JEKYLL_ENV=production bundle exec jekyll build`; the generated site lives in `_site`.