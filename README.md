# sw13tch-dio.github.io

Personal dev site for **Dio Brown** (sw13tch).
Lives at https://sw13tch-dio.github.io.

## What this is

A bare-bones single-file HTML site with a 90s file-tree navigation aesthetic. Hosts:

- About / contact
- Ongoing research (currently: Psychomechia)
- Links to GitHub & LinkedIn

Built fast on May 1, 2026. Polish later. The lab-room interactive concept lives separately in the `dio-site` repo.

## Hosting

GitHub Pages, served from the `main` branch root. Push and it deploys automatically (~30-60s).

## Custom domain (when ready)

1. Buy domain (Namecheap / Cloudflare / Porkbun)
2. Add a `CNAME` file to this repo containing the domain (one line, no protocol)
3. In domain registrar, add four `A` records pointing to GitHub Pages:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
4. In repo settings → Pages → Custom domain, paste the domain. Enable HTTPS.

## Editing

Single file: `index.html`. Edit, push, done.

## Stack

- One HTML file
- One CSS block
- One vanilla JS hash router
- Zero build step
