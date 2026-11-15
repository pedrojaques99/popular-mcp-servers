# Most Popular Model Context Protocol (MCP) Servers

This repository contains a curated list of the most popular Model Context Protocol (MCP) servers based on usage data from [Smithery.ai](https://smithery.ai/).

## What is MCP?

The Model Context Protocol (MCP) is an open standard developed by Anthropic that enables developers to build secure, two-way connections between their data sources and AI-powered tools. It allows AI assistants like Claude to access external tools, data sources, and APIs.

## Top MCP Servers by Usage

Based on the usage data from Smithery.ai, here are the most popular MCP servers:

1. **Sequential Thinking** (5,550+ uses) - [@smithery-ai/server-sequential-thinking](https://smithery.ai/?q=sequential-thinking)
   - Provides a tool for dynamic and reflective problem-solving through a structured thinking process

2. **wcgw** (4,920+ uses) - Shell and coding agent on Claude and ChatGPT

3. **Github** (2,890+ uses) - [@smithery-ai/github](https://smithery.ai/?q=github)
   - Access the GitHub API, enabling file operations, repository management, search functionality, and more

4. **Brave Search** (680+ uses) - [@smithery-ai/brave-search](https://smithery.ai/?q=brave-search)
   - Integrate web and local search capabilities

5. **Web Research** (533+ uses) - [@mzxrai/mcp-webresearch](https://smithery.ai/?q=webresearch)
   - Augments LLMs with better research capabilities, providing Google search integration, webpage content extraction, research session tracking and more

6. **iTerm** (402+ uses) - [iterm-mcp](https://smithery.ai/?q=iterm)
   - Execute commands in the current iTerm session

7. **TaskManager** (374+ uses) - [@kazuph/mcp-taskmanager](https://smithery.ai/?q=taskmanager)
   - Model Context Protocol server for Task Management, allowing Claude Desktop (or any MCP client) to manage and execute tasks in a queue-based system

8. **SQLite Server** (274+ uses) - [mcp-server-sqlite-npx](https://smithery.ai/?q=sqlite)
   - A Node.js implementation of the Model Context Protocol SQLite server, providing an npx-based alternative for environments lacking Python's UVX runner

9. **Fetch** (269+ uses) - [@smithery-ai/fetch](https://smithery.ai/?q=fetch)
   - A simple tool that performs a fetch request to a webpage

10. **Knowledge Graph Memory Server** (263+ uses) - [@smithery-ai/memory](https://smithery.ai/?q=memory)
    - Enable persistent memory using a local knowledge graph

11. **Playwright** (257+ uses) - [@executeautomation/playwright-mcp-server](https://smithery.ai/?q=playwright)
    - Provides browser automation capabilities using Playwright, enabling LLMs to interact with web pages, take screenshots, and execute JavaScript in a browser environment

12. **Dice Roller** (246+ uses) - [mcp-dice](https://smithery.ai/?q=dice)
    - Roll dice using standard dice notation and return results with their total sum

13. **Desktop Commander** (199+ uses) - [@wonderwhy-er/desktop-commander](https://smithery.ai/?q=desktop-commander)
    - Execute terminal commands and manage files with editing capabilities

14. **Exa** (171+ uses) - [exa](https://smithery.ai/?q=exa)
    - Bring knowledge to your AI via the Exa Search API for real-time semantic web searches

15. **Obsidian Reader** (144+ uses) - [mcp-obsidian](https://smithery.ai/?q=obsidian)
    - Read and search within a directory of Markdown notes in an Obsidian vault

16. **MySQL Server** (131+ uses) - [@f4ww4z/mcp-mysql-server](https://smithery.ai/?q=mysql)
    - A Model Context Protocol server for MySQL database operations

17. **Shodan Server** (131+ uses) - [@burtthecoder/mcp-shodan](https://smithery.ai/?q=shodan)
    - A Model Context Protocol server for querying the Shodan API and Shodan CVEDB, providing access to network intelligence and security services

18. **Audiense Insights** (81+ uses) - [@AudienseCo/mcp-audiense-insights](https://smithery.ai/?q=audiense)
    - Extract marketing insights and audience analysis from Audiense reports

## Other Notable MCP Servers

While not in the top usage list, these MCP servers are also worth mentioning:

- **AWS S3** - A sample MCP server for AWS S3 that flexibly fetches objects from S3 such as PDF documents
- **Airtable** - Read and write access to Airtable databases, with schema inspection
- **Docker** - Integrate with Docker to manage containers, images, volumes, and networks
- **Google Calendar** - Integration with Google Calendar to check schedules, find time, and add/delete events
- **Kubernetes** - Connect to Kubernetes cluster and manage pods, deployments, and services
- **MongoDB** - A Model Context Protocol Server for MongoDB
- **Notion** - Interact with Notion API
- **Qdrant** - Vector search engine integration for semantic memory storage and retrieval
- **[No Stairs Please MCP](https://nostairsplease.com/mcp)** - Remote Streamable HTTP MCP server for searching independent live music venues, tour routes, and booking contacts

## Resources for MCP

- [Smithery.ai](https://smithery.ai/) - A registry of MCP servers
- [MCP Reference Servers](https://github.com/smithery-ai/reference-servers) - Official repository with reference implementations
- [Model Context Protocol Documentation](https://modelcontextprotocol.io/) - Official documentation

## Contributing

Feel free to submit a pull request to add more MCP servers to this list or update usage statistics.

## License

This repository is licensed under the MIT License - see the LICENSE file for details.