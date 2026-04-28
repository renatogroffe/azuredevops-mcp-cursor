# azuredevops-mcp-cursor
Configurações para uso do MCP Server do Azure DevOps com Cursor.

```json
{
  "mcpServers": {
    "mcp-azuredevops": {
      "command": "npx",
      "args": ["-y", "@azure-devops/mcp", "organization-name"],
      "env": {
        "AZURE_DEVOPS_PAT": "PAT_AZDEVOPS"
      }
    }
  }
}
```