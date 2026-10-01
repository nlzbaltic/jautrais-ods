# Jautrais Ods — mājaslapas prototips

Statiska lapa (HTML + WebP bildes). Hostēta Cloudflare Pages, savienota ar šo GitHub repo.

**Cloudflare iestatījumi (Workers ar statiskajiem failiem)**
- Build command: (tukšs)
- Deploy command: `npx wrangler deploy`
- Lapas faili ir mapē `public/`, konfigurācija `wrangler.jsonc`

Lapa ir ar `noindex`, lai prototips neparādītos Google. Kad būs gatava Next.js + Sanity versija, šo repo aizstās.
