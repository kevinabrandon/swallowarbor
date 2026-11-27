# swallowarbor.com

The public page for Swallow Arbor, served by GitHub Pages at https://swallowarbor.com.

Plain static HTML, no build step: edit `index.html`, push to `main`, and Pages redeploys it in about a minute.

- `CNAME` tells GitHub Pages which custom domain this site answers to. Do not delete it; Pages reads it on every deploy.
- `.nojekyll` disables the Jekyll build so that dot-directories such as `.well-known/` are served as-is.

The domain is registered at GoDaddy and its DNS is at Cloudflare. The records, the Bluesky handle that uses the domain, and the deployment notes are in the private homelab repo under `services/swallowarbor/`.

## Look

The page follows the Swallow Arbor design (Dusk theme, Young Serif for the name, Figtree for text). `swallow.css`
is a copy of the shared stylesheet generated in the homelab repo (`design/swallow.css`); replace it from there
rather than editing it here. The photo in `img/` is the view west at sunset, with its location metadata
removed; anything added to this public repo must not identify the house.
