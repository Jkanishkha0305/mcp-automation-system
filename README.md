
<div align="center">
  <h1>MCP Automation System</h1>
  <h3>Enterprise-grade automation system using Model Context Protocol</h3>
</div>

</br>

## 📖 About

The **MCP Automation System** is a production-ready AI automation platform built with the **Model Context Protocol (MCP)**. This system demonstrates how to build modular, scalable automation workflows that integrate multiple tools and services.

The system focuses on automating Pull Request reviews by connecting GitHub, Slack, Asana, and AI models through a unified MCP architecture.

### 🎯 Features

- **Custom MCP Servers** for Slack and Asana integration
- **GitHub MCP integration** for pull request analysis
- **Tool Registry** - centralized catalog of all available tools and prompts
- **Custom MCP Host** with Gemini AI for intelligent orchestration
- **Webhook-driven automation** for real-time PR reviews

### 🛠 What's Inside

- **Build custom MCP Servers** exposing enterprise APIs
- **Connect external MCP servers** and integrate them seamlessly
- **Centralize tools** into a global Tool Registry
- **Custom MCP Host** for workflow orchestration
- **Scalable automation** ready for production

## 🏗️ Repository Structure

```bash
mcp-automation-system/
├── apps/
│   ├── pr-reviewer-mcp-host/      # MCP host & client manager
│   └── pr-reviewer-mcp-servers/   # MCP servers (GitHub, Slack, Asana, Tool Registry)
├── LICENSE
└── README.md
```

## 🚀 Getting Started

Detailed setup instructions for each component:

| Application                                                               | Documentation |
|---------------------------------------------------------------------------|---------------|
| MCP Host & Client Connection Manager                                     | [apps/pr-reviewer-mcp-host](apps/pr-reviewer-mcp-host) |
| Modular MCP Servers (GitHub, Slack, Asana, Prompts) & Tool Registry     | [apps/pr-reviewer-mcp-servers](apps/pr-reviewer-mcp-servers) |

## 🎓 Prerequisites

| Category    | Requirements                                                                                                                     |
|-------------|----------------------------------------------------------------------------------------------------------------------------------|
| **Skills**  | Python (Intermediate), REST APIs (Beginner), Basic AI/LLM knowledge (Beginner) |
| **Hardware**| Modern laptop/PC (no GPU required)                                        |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
