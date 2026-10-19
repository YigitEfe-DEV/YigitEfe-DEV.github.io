# efeyigit.me

Personal portfolio source for [efeyigit.me](https://efeyigit.me), served via GitHub Pages.

Source builds at [`portfolio-work/site/`](https://github.com/YigitEfe-DEV) — Vite + React + TypeScript. This repository carries the built artifact only.

## Updating

```bash
cd /path/to/portfolio-work/site
pnpm build       # → dist/
# then sync dist/* into this repo's root, commit, and push to main.
```

GitHub Pages automatically publishes `main` to `efeyigit.me` thanks to the `CNAME` file at the repo root.