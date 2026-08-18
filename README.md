Install this mcp server by adding the folowing JSON code to your JSON config file

```json

"mcpServers": {
    "MemoriesTwo": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/GajenderKalyan/Chess-mcp-Gajender.git",
        "chess"
        "env": {
        "SystemRoot": "C:\\Windows",
        "USERPROFILE": "C:\\Users\\gajen",
        "APPDATA": "C:\\Users\\gajen\\AppData\\Roaming",
        "LOCALAPPDATA": "C:\\Users\\gajen\\AppData\\Local",
        "TEMP": "C:\\Users\\gajen\\AppData\\Local\\Temp",
        "TMP": "C:\\Users\\gajen\\AppData\\Local\\Temp"
        }
      ]
    }
  }