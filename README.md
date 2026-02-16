# slidev-theme-kirei

A clean, minimal [Slidev](https://github.com/slidevjs/slidev) theme with Japanese typography support.

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

<pre><code>---
theme: <b>kirei</b>
---</code></pre>

Learn more about [how to use a theme](https://sli.dev/guide/theme-addon#use-theme).

## Layouts

- **default** - Standard slide
- **cover** - Title slide
- **intro** - Introduction slide
- **section** - Section divider
- **two-cols** - Two column layout
- **three-cols** - Three column layout
- **center** - Centered content
- **quote** - Blockquote style
- **fact** - Key fact / number highlight
- **statement** - Bold statement
- **end** - Closing slide

## Fonts

- Sans: Noto Sans JP
- Mono: JetBrains Mono

## Development

- `npm install`
- `npm run dev` to start theme preview of `example.md`
- Edit the `example.md` and style to see the changes
- `npm run export` to generate the preview PDF
- `npm run screenshot` to generate the preview PNG
