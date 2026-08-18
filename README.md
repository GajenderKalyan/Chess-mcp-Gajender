Install this mcp server by adding the folowing JSON code to your JSON config file

```json

"mcpServers": {
    "MemoriesTwo": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/GajenderKalyan/Chess-mcp-Gajender.git",
        "chess"
      ]
    }
  }