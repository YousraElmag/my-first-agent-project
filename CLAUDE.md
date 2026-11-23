# CLAUDE.md

Guidance for Claude when working in this project.

## Project

A simple static website. Pages are opened directly in the browser; there is no build step.

## Stack

- HTML and CSS only
- No frameworks

## Structure

```
index.html      Home page
about.html      About page (add new pages in the root folder)
css/style.css   The only stylesheet
images/         Images and icons
README.md       Project description
```

## Conventions

- Use semantic HTML: `header`, `nav`, `main`, `section`, `article`, `footer`, etc. Avoid `div` when a semantic element fits.
- Every image needs a meaningful `alt` attribute.
- Put all CSS in `css/style.css`. Every page links to it with `<link rel="stylesheet" href="css/style.css">`.
- No inline styles (no `style="..."` attributes and no `<style>` blocks in HTML).
- Write all comments in English.
- Use lowercase file names with hyphens, e.g. `contact-us.html`.
- Reuse the color variables in `:root` in `style.css` instead of hard-coding new colors.
- Keep the shared header, navigation and footer the same on every page.

## Do not

- Add JavaScript frameworks or libraries (React, Vue, jQuery, etc.).
- Add build tools or package managers (npm, Vite, Webpack, Sass, etc.).

## Git

- Always ask before making a git commit or push.
