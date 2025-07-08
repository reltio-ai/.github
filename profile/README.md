# 👋 Welcome to Reltio AI

We’re building the foundation for **agentic AI** in the enterprise — where intelligent agents can take action on trusted, real-time data using secure, standardized interfaces.

## ⚙️ What is AgentFlow?

**AgentFlow** is Reltio’s next-generation Agentic AI platform, combining secure, real-time data from Reltio’s Intelligent Data Graph with autonomous and interactive AI agents.

It enables a new class of digital workers (resolvers, enrichers, verifiers, etc.) that can perform complex data stewardship operations with minimal human input — all while ensuring strict governance, traceability, and compliance.

AgentFlow is powered by **Model Context Protocol (MCP)**.

---

## 🔌 What is the Model Context Protocol (MCP)?

MCP is an **open standard** that allows AI agents (LLMs, orchestrators, or tools like Claude, LangChain, CrewAI) to discover and invoke secure APIs — called “tools” — in a structured and semantically rich way.

Reltio’s implementation of MCP lets agents interact with enterprise master data (search, match, merge, enrich, etc.) without needing custom APIs or unsafe exports.

---

## 🚀 The Reltio MCP Server

### 🧪 MCP Developer Edition (You're here!)
This open-source edition is perfect for developers, AI hackers, and partners who want to:

- Experiment with AI agents using real Reltio environments
- Build and test new tools with MCP-compatible clients
- Extend the server to add custom logic or tools
- Self-host locally or in your cloud

🔗 **Get started now:**  
👉 [Reltio MCP Server - Developer Edition](https://github.com/reltio-ai/reltio-mcp-server)

📚 Full setup in minutes:  
```bash
git clone https://github.com/reltio-ai/reltio-mcp-server.git
cd reltio-mcp-server
cp .env.sample .env  # Add your Reltio client credentials
bash setup.sh        # Mac/Linux OR setup.bat for Windows
