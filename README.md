# Helicon Site

Landing publica da Helicon Labs, feita com Astro.

## Objetivo

Publicar o posicionamento institucional da Helicon Labs.

## Stack

1. Astro (static output)
2. CSS custom
3. `pnpm` via Corepack
4. Deploy em Cloudflare Pages

## Setup Local

```bash
corepack enable
corepack prepare pnpm@10.4.0 --activate
pnpm install
pnpm dev
```

## Build

```bash
pnpm build
```

Saida: `dist/`

## Deploy (Cloudflare Pages)

1. Build command: `pnpm build`
2. Output directory: `dist`
3. Node.js: `22`

## Relacionados

1. Organizacao: https://github.com/HeliconLabs
2. Produto/spec Fleetu: https://github.com/HeliconLabs/fleetu-ideacao
