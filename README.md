# claimward.github.io

The Claimward landing page, built with [Hugo](https://gohugo.io/) and published
to GitHub Pages at <https://claimward.github.io/>.

It's a single-page site with a custom layout (no external theme) — content and
copy live in `hugo.toml` params, markup in `layouts/index.html`, styles in
`static/css/style.css`.

## Local preview

```sh
hugo server      # http://localhost:1313
```

## Build

```sh
hugo --minify    # output in ./public
```

## Deploy

`.github/workflows/hugo.yml` builds and deploys on every push to `main`. Enable
**Settings → Pages → Source → GitHub Actions** once.

The versioned product docs are a separate project (the `docs` repo) published at
`/docs/`.

## License

BSD 3-Clause.
