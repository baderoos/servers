This is a monorepo for Model Context Protocol (MCP) servers. The servers are written in TypeScript and Python.

**Project Structure:**

The `src` directory contains the individual servers, each in its own subdirectory. Each server is a separate workspace.

**Available Workspaces:**

*   `@modelcontextprotocol/server-everything`
*   `@modelcontextprotocol/server-memory`
*   `@modelcontextprotocol/server-filesystem`
*   `@modelcontextprotocol/server-sequential-thinking`

**Building and Running:**

*   To build all servers, run `npm run build`.
*   To watch for changes and rebuild, run `npm run watch`.
*   To publish all servers, run `npm run publish-all`.
*   To link all workspaces, run `npm run link-all`.
