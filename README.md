# Kirk Digital Holdings – Autokirk UI

This is the frontend for the Autokirk OS Business Blueprint Generator.
It is designed to be deployed on Netlify and mapped to `kirkdigitalholdings.com`.

## Files

- `index.html` – single-page UI with a textarea and button
- Calls an MCP backend at `/mcp/generate-ais-blueprint`

## Setup

1. Create a GitHub repo (e.g. `kirkdigitalholdings-ui`) and upload these files.
2. Connect the repo to Netlify and deploy.
3. In `index.html`, set `MCP_URL` to your live Render backend URL.
4. In Netlify domain settings, map the site to `kirkdigitalholdings.com`.
