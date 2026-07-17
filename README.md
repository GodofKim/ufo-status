# UFO Status

Public status page for [UFO](https://ufo.alienz.ooo) — hosted **off Cloudflare**
(GitHub Pages) on purpose, so it stays up and can explain what's wrong when
Cloudflare itself is having an incident.

All checks run client-side in your browser:
- `ufo.alienz.ooo/api/health` (shallow + deep component probe)
- Cloudflare's own status API, filtered to the products UFO runs on

Live at https://status.alienz.ooo
