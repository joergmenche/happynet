# HappyNet

A minimal static landing page for a short introduction to complex networks.

## Run locally

The site uses plain HTML and CSS. Serve the repository root with any
static file server, for example:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

The included GitHub Actions workflow publishes the repository root to GitHub
Pages whenever `main` is updated. In the repository settings, set **Pages → Source**
to **GitHub Actions** once, then visit:

<https://joergmenche.github.io/happynet/>
