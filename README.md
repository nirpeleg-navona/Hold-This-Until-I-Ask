# Hold This Until I Ask — site package

- `hold-this-until-i-ask.html` — the essay. Self-contained apart from Google Fonts (Barlow). Light and dark follow the reader's system setting.
- `blocks/` — the two interactive simulations. The essay embeds them as iframes with `?embed` (hides their kicker, tightens padding); each block posts its height to the parent, so the iframes fit their content. They also work as standalone pages at `blocks/<file>.html`, which is the URL to give LinkedIn and Substack readers.
- `img/` — essay images at 1600 px (JPEG) and the four-statements diagram as SVG with the fonts embedded (light and dark variants).
- `media/` — GIFs (under 5 MB, LinkedIn's limit) and the 3× feed videos, for hosting if LinkedIn articles need a GIF by URL.

Keep the folder structure; paths are relative. The Open Graph image tag points at `img/hero.jpg` relative to the page; make it absolute once the page has its URL.
