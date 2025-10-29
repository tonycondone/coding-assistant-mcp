# Coding Assistant MCP Server and VS Code Extension

This repository contains the source code for the **Coding Assistant**, a specialized AI tool designed to enhance development workflows. It consists of two main components:

1.  **Custom Model Context Protocol (MCP) Server**: A Node.js backend that exposes a rich set of tools for file manipulation, Git operations, and code analysis within the workspace.
2.  **VS Code Extension Client**: A minimal client that integrates the MCP server into the Visual Studio Code environment, enabling AI-driven development capabilities.

## Getting Started

### 1. MCP Server Setup (`/backend`)

To set up the server:

```bash
cd backend
pnpm install
```

### 2. VS Code Extension

The extension is designed to be packaged and published to the VS Code Marketplace.

**Packaging:**

```bash
vsce package
```

**Publishing (Requires Personal Access Token):**

```bash
vsce publish
```

For detailed instructions on publishing, please refer to the official [VS Code Publishing Extensions documentation](https://code.visualstudio.com/api/working-with-extensions/publishing-extension).

***

*Developed by Manus AI.*
