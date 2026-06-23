<div align="center">

*Name a mood. Get a painting from the Met's open collection that already carries it.*

<br>

[![Live demo](https://img.shields.io/badge/%E2%96%B6_live_demo-saf--lab.github.io-c9a24b?style=flat-square&labelColor=0e0e0e)](https://saf-lab.github.io/someonepaintedthisbefore/)
&nbsp;
![Built with vanilla JS](https://img.shields.io/badge/built_with-vanilla_JS-e8e8e8?style=flat-square&labelColor=0e0e0e)
&nbsp;
![Data: The Met Open Access](https://img.shields.io/badge/data-The_Met_Open_Access-b89758?style=flat-square&labelColor=0e0e0e)
&nbsp;
![Build: none required](https://img.shields.io/badge/build-none_required-6b6b6b?style=flat-square&labelColor=0e0e0e)
&nbsp;
![Hosted on GitHub Pages](https://img.shields.io/badge/hosted-GitHub_Pages-4a4a4a?style=flat-square&labelColor=0e0e0e)

</div>

---

## What it does

You're shown five mood words — `melancholy`, `defiant`, `awestruck`, `homesick`, and so on — drawn at random from a curated set. Pick one, pick several, or ignore them entirely and type your own word. The app reaches into the Metropolitan Museum of Art's open collection, finds a painting that matches the feeling, and hands you one back: the image, its title, the artist, the year, and a one-line caption tying it to what you said you were feeling.

<div align="center">

`melancholy` &nbsp;·&nbsp; `restless` &nbsp;·&nbsp; `tender` &nbsp;·&nbsp; `reverent` &nbsp;·&nbsp; `homesick` &nbsp;·&nbsp; `defiant` &nbsp;·&nbsp; `awestruck` &nbsp;·&nbsp; `numb`

</div>

---

## Built with

| | |
|---|---|
| **Frontend** | Vanilla HTML, CSS & JavaScript — no frameworks, no dependencies, no build tooling |
| **Artwork** | [The Met Collection API](https://metmuseum.github.io/) · open access, no key required |
| **Word expansion** | [Datamuse API](https://www.datamuse.com/api/) · no key required |
| **Type & palette** | Cormorant Garamond over a near-black gallery wall |
| **Hosting** | GitHub Pages |

Because both APIs are public and keyless, the entire app is a single static page you can open locally or drop on any static host.

---

## Run it locally

```bash
git clone https://github.com/saf-lab/someonepaintedthisbefore.git
cd someonepaintedthisbefore
open index.html   # or just double-click it
```

`index.html` is fully self-contained; CSS and JavaScript are inline.

---

## Repository notes

- **`index.html`** — the live app. Self-contained; this is what GitHub Pages serves.
- **`style.css`** / **`script.js`** — an earlier *address-based* prototype (enter an address → find a Met painting whose place-name matches somewhere near you). These files are **not loaded by `index.html`** and aren't part of the current app. Kept for reference; safe to remove for a cleaner repo.
- **`banner.png`** — the header image above. Keep it in the repo root so this README renders it.

<div align="center">
<br>

**[ Try it → saf-lab.github.io/someonepaintedthisbefore ](https://saf-lab.github.io/someonepaintedthisbefore/)**

</div>
