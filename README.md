# swallowarbor.com

The public page for Swallow Arbor, served by GitHub Pages at https://swallowarbor.com.

Plain static HTML, no build step: edit `index.html`, push to `main`, and Pages redeploys it in about a minute.

- `CNAME` tells GitHub Pages which custom domain this site answers to. Do not delete it; Pages reads it on every deploy.
- `.nojekyll` disables the Jekyll build so that dot-directories such as `.well-known/` are served as-is.

The DNS for the domain lives at GoDaddy. The records, the Bluesky handle that uses the domain, and the deployment notes are in the private homelab repo under `services/swallowarbor/`.
