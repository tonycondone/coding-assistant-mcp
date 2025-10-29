# Coding Assistant MCP Server & VS Code Extension

A dedicated repository for the **Coding Assistant**, an AI-powered tool designed to streamline development workflows.

This project comprises two core components:

1.  **Custom MCP Server** (Node.js): A backend that provides the AI agent with powerful tools for workspace interaction.
    *   **File Management**: Read, write, and list files.
    *   **Code Analysis**: Basic structural analysis (functions, imports).
    *   **Version Control**: Full Git integration (status, diff, commit, log).

2.  **VS Code Extension Client**: The client that integrates the MCP server's capabilities directly into the Visual Studio Code environment.

## 🚀 Quick Start

### 1. Server Setup (`/backend`)

The server is a Node.js application.

| Command | Description |
| :--- | :--- |
| `cd backend` | Navigate to the server directory. |
| `pnpm install` | Install dependencies. |
| `node mcp-server.js` | Run the server on `stdio`. |

### 2. VS Code Extension

The extension is ready for packaging and publishing.

| Command | Description |
| :--- | :--- |
| `vsce package` | Create the VSIX file for installation. |
| `vsce publish` | Publish to the VS Code Marketplace (requires PAT). |

For detailed publishing instructions, please see the [official VS Code documentation](https://code.visualstudio.com/api/working-with-extensions/publishing-extension).

***

*Developed by Manus AI.*
