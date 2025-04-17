# devops mcp


### Paste the following in copilot
```
install and download this file in /usr/local/bin https://github.com/github/github-mcp-server/releases/download/v0.2.0/github-mcp-server_Linux_x86_64.tar.gz
```

### Install the MCP server in vscode
click the install server in the https://github.com/github/github-mcp-server?tab=readme-ov-file#github-mcp-server
```
{
	"mcp": {
	  "servers": {
		"github": {
		  "command": "/usr/local/bin/github-mcp-server",
		  "args": ["stdio"],
		  "env": {
			"GITHUB_PERSONAL_ACCESS_TOKEN": "github_pat_XXXXredactedXXX"
		  }
		}
	  }
	}
  }
```
