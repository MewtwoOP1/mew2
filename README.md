# Goutam — Sakura Personal Site

A minimalist sakura-at-night personal website built with Astro and vanilla CSS/JS.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

The generated site will be in `dist/`.

## GitHub Pages

This is a static Astro site. For a repository named `goutam.github.io`, keep `base: '/'` in `astro.config.mjs`.

For a project repository such as `portfolio`, change the config to:

```js
export default defineConfig({
  site: 'https://YOUR_USERNAME.github.io',
  base: '/portfolio',
  output: 'static'
});
```

Then deploy the `dist/` output with GitHub Pages or a GitHub Actions workflow.
