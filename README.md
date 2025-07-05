#installation steps

To install "Demo" MCP server, run the following command:

'''json'
{
  "mcpServers": {
    "Demo": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/karanveera28/DemoMCPServer2.git",
        "mcp-server"
      ]
    }
  }
}