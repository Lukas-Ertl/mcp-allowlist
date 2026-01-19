# MCP Registry (Allowlist)

Statische MCP-Registry im JSON-Format (Schema v0.1) als Allowlist für GitHub Copilot. GitHub Pages liefert `/v0.1/servers/index.json` unter `/v0.1/servers` aus.

## Nutzung
- GitHub Pages URL nach Deployment (ersetze `<user>`): https://<user>.github.io/mcp-registry/v0.1/servers
- Copilot kann das JSON direkt von dort abrufen (CORS-freundlich, keine Auth).

## Deployment
- Jeder Push auf `main` deployt den Inhalt von `v0.1` nach GitHub Pages.
- Workflow: `.github/workflows/deploy-pages.yml`.

