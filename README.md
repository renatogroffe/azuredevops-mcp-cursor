# azuredevops-mcp-cursor
Configurações para uso do MCP Server do Azure DevOps com Cursor.

Arquivo **mcp.json** (diretório **.cursor**):

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

Package npm: **https://www.npmjs.com/package/@azure-devops/mcp**

Exemplo de consulta aos repositórios de um projeto:

![MCP do Azure DevOps](img/cursor-mcp-azdevops-01.png)