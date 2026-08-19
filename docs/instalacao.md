# Instalação detalhada

SEFAZ AL: IPVA (ano atual) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sefaz_al_ipva`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sefaz_al_ipva` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sefaz_al_ipva` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sefaz_al_ipva` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sefaz_al_ipva` (ou `servers.sefaz_al_ipva` no VS Code) do config do cliente e reinicie.
