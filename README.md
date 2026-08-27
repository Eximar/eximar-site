# eximar-site

Landing page for Eximar. A single static `index.html` with no build step and no dependencies.

## Local preview

Open `index.html` in a browser, or serve the directory:

```sh
python -m http.server 8000
```

## Deploy

The site deploys to Vercel as a static site with no configuration:

```sh
vercel --prod
```

Or connect the repository in the Vercel dashboard; no framework preset or build command is needed.
