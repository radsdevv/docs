# VibeKast docs

Source for the VibeKast documentation, built with [Mintlify](https://mintlify.com).

## Preview locally

```bash
npm i -g mint
mint dev
```

Then open http://localhost:3000.

## Check before pushing

```bash
mint validate
mint broken-links
```

## Structure

- `docs.json`: navigation, theme and settings
- `*.mdx`: guide pages
- API reference pages are generated from the live spec at https://www.vibekast.xyz/openapi.json, so they update when the API does.

Pushes to `main` deploy automatically through the Mintlify GitHub app.
