# Tundra Hunt

Static page that ranks used Toyota Tundra CrewMax 4x4 5.7L listings by deal score.
Live at https://tundra.tannylab.com (Cloudflare Workers static assets).

- Page: `public/index.html` (listing data is the `PAYLOAD` constant in the script)
- Deploy: `npx wrangler@4 deploy`
- Refresh: ask Claude to "Refresh the Tundra hunt"; it updates `PAYLOAD`, commits and redeploys.
