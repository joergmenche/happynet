# HappyNet

An interactive Three.js presentation about complex networks. Its scenes introduce
nodes, links, shortest paths, hubs, leaf nodes, communities, and bridges.

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
