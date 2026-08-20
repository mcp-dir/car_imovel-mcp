# Instalação detalhada

Cadastro Ambiental Rural: Imóvel é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_car_imovel`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_car_imovel` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_car_imovel` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_car_imovel` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.car_imovel` (ou `servers.car_imovel` no VS Code) do config do cliente e reinicie.
