# HappyNet

An interactive 17-scene Three.js presentation about complex networks. A consistent
decimal chapter sequence (`0.1`–`5.5`) introduces nodes, links, shortest paths,
hubs, leaf nodes, communities, and bridges.

## Run locally

The visualization is contained in `index.html` and loads Three.js plus OrbitControls
from pinned CDN URLs. Serve the repository root with any static file server, for example:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

GitHub Pages publishes the repository root automatically whenever `main` is
updated. The live site is available at:

<https://joergmenche.github.io/happynet/>
