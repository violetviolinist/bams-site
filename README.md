# BAMS Website

Static website for **Bombay Academy of Management Studies** — Corporate Mind Management & Human Performance Training since 1986.

## Development

```sh
npm install
npm run dev      # Start dev server
npm run build    # Build static site to dist/
npm run preview  # Preview production build
```

## Docker

```sh
docker build -t bams-site .
docker run -p 3000:3000 bams-site
```

## Deployment

Automated via GitHub Actions on push to `main`. Requires these repository secrets:

- `VPS_HOST` — server IP/hostname
- `VPS_USER` — SSH username
- `VPS_SSH_KEY` — private SSH key

The container listens on port 3000. Point your Caddy reverse proxy to `127.0.0.1:3000`.
