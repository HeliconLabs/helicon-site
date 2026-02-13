# Helicon Site

Public landing page for Helicon Labs, built with Astro.

## Stack

- Astro (static output)
- Custom CSS (no framework dependency)
- Package manager: pnpm (via Corepack)
- Deploy target: Cloudflare Pages

## Local Setup

```bash
corepack enable
corepack prepare pnpm@10.4.0 --activate
pnpm install
```

## Run Local

```bash
pnpm dev
```

## Build

```bash
pnpm build
```

Output directory: `dist/`

## Deploy on Cloudflare Pages

1. Create a new Pages project and connect this repository.
2. Build command: `pnpm build`
3. Build output directory: `dist`
4. Node.js version: `22`
5. Add custom domain: `heliconlabs.dev`

## Links

- GitHub org: https://github.com/HeliconLabs
- Product docs/spec: https://github.com/HeliconLabs/fleetu-ideacao
