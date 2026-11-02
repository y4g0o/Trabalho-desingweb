🇺🇸 English · [🇧🇷 Português](README.pt-BR.md)

# Trabalho-desingweb

Four static interface screens built with only HTML and CSS (no JavaScript, no frameworks) for a college Web Design assignment.

## Context

This was the first assignment ("Trabalho 1") of a Web Design course in college: recreate a few screens using just HTML and CSS. All screens share the [Catppuccin Mocha](https://catppuccin.com) color palette. The content (songs, channels, files) is fictional, and the screens are static mockups: buttons and inputs do nothing.

## What's inside

Each folder is one screen with its own `index.html` and `style.css`:

| Folder | Screen |
| --- | --- |
| `mobile-e-impressora3d/` | Item 1: a mobile music player screen ("NovaTune") and a desktop-style menu for a 3D printer app |
| `layout-colorido/` | Item 2: a grid of Catppuccin Mocha colors with names and hex codes |
| `gerenciador-arquivos/` | Item 3: a desktop file manager window (title bar, toolbar, breadcrumb, sidebar, file list, status bar) |
| `novacast-youtube/` | Item 4: a YouTube-style video search results page ("NovaCast") with header, sidebar and video card grid |

## How to run

No build step or dependencies. Clone the repo and open any `index.html` in a browser, for example:

```bash
git clone https://github.com/y4g0o/Trabalho-desingweb.git
cd Trabalho-desingweb
xdg-open novacast-youtube/index.html   # Linux; use "open" on macOS or double-click on Windows
```

## What I learned / next steps

- Building full layouts (headers, sidebars, grids, cards, window chrome) with plain HTML and CSS, and reusing one color palette across several screens.
- Next: make the screens responsive. There is no `<meta name="viewport">` or media query yet, so they are designed for a desktop viewport.
- Next: improve accessibility and semantics, e.g. `aria-label` on icon-only buttons, labels on inputs, and elements like `<header>`, `<nav>` and `<main>` instead of generic `<div>`s.
- Next: give each page a descriptive `<title>` (they are currently "Item 1" to "Item 4") and add a root `index.html` linking the four screens.

## Feedback and contributions welcome

Feedback on the HTML/CSS is welcome. Feel free to open an issue or a small pull request, especially for accessibility or responsiveness fixes. Please keep it to HTML and CSS only, since that was the rule of the assignment.

## License

[MIT](LICENSE) © Yago Macambira
