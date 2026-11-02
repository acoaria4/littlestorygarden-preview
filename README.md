# Little Story Garden — design preview

[Compare the three designs](https://acoaria4.github.io/littlestorygarden-preview/)

A public review page for three Little Story Garden concepts: Sunlit Garden, Moonlit Garden, and Botanical Press. The development project and handoff are maintained separately in a private repository.

![The three design concepts](preview.png)

## Try it

Compare all three concepts side by side. Use **Expand** to inspect one design, **Screen** to switch between desktop and mobile, and **Peek inside** to browse an existing sample page. Creation buttons demonstrate name entry only. **Prefer this design** marks a choice on the page; it does not send feedback. Send your preferred name and thoughts to the person who shared the link.

## Scope

This is an early design comparison, not an ordering website. It does not upload photographs, generate illustrations, accept payments, or place orders. No final direction has been chosen.

The site is static HTML, CSS, and JavaScript, with embedded sample artwork from the owner's original Inara alphabet book. No original family photographs, project handoff, reference snapshots, credentials, or private development history are included. No general reuse licence is granted for the artwork or project.

## Run locally

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Open `http://127.0.0.1:4173/`. Stop the server with Ctrl+C. No build or package installation is required. Google Fonts supplies Fraunces and DM Sans when online, with Georgia and system sans-serif fallbacks.

## Files and hosting

`index.html` is the complete review page, `preview.png` illustrates this README, `.nojekyll` enables static publishing, and `robots.txt` discourages indexing. GitHub Pages publishes the `main` branch from `/`. The site and this repository are public; indexing directives are not access controls.
