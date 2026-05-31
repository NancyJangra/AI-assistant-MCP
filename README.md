# 🚀 AI Assistant MCP

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge\&logo=python)
![MCP](https://img.shields.io/badge/MCP-Agentic_AI-purple?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-Framework-green?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-LLM-orange?style=for-the-badge)
![Playwright](https://img.shields.io/badge/Playwright-Browser_Automation-darkgreen?style=for-the-badge)
![DuckDuckGo](https://img.shields.io/badge/DuckDuckGo-Web_Search-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Learning_Project-red?style=for-the-badge)

An AI-powered assistant built using **MCP (Model Context Protocol)**, **LangChain**, and **Groq** to explore modern **Agentic AI workflows**.

This project demonstrates how an AI agent can:

* use external tools,
* perform browser automation,
* search the web,
* maintain conversation memory,
* and interact intelligently through MCP servers.

---

# ✨ Features

✅ MCP-based AI Agent
✅ Tool Calling with MCP Servers
✅ Browser Automation using Playwright
✅ Web Search Integration
✅ Conversation Memory
✅ Async Python Architecture
✅ Groq LLM Integration
✅ Interactive Terminal Chat

---

# 🧠 What I Learned

This project helped me understand:

* Agentic AI workflows
* MCP Client & MCP Server architecture
* Tool calling
* Async programming with `asyncio`
* LangChain integrations
* Environment variables and `.env`
* AI agent memory systems
* Real-world debugging in AI systems

---

# 🛠️ Tech Stack

| Technology     | Purpose                     |
| -------------- | --------------------------- |
| Python         | Core programming language   |
| MCP            | Tool communication protocol |
| LangChain      | AI orchestration framework  |
| Groq           | LLM provider                |
| Playwright MCP | Browser automation          |
| DuckDuckGo MCP | Web search                  |
| asyncio        | Async execution             |

---

# 📂 Project Structure

```bash
AI-assistant-MCP/
│
├── app.py
├── browser_mcp.json
├── .env
├── .gitignore
├── pyproject.toml
├── README.md
└── uv.lock
```

---

# ⚙️ Setup Instructions

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/AI-assistant-MCP.git

cd AI-assistant-MCP
```

---

## 2️⃣ Install Dependencies

```bash
uv add mcp-use langchain-groq python-dotenv
```

---

## 3️⃣ Create `.env` File

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
```

---

## 4️⃣ Configure MCP Servers

Update `browser_mcp.json`:

```json
{
  "mcpServers": {
    "playwright": {
      "command": "npx",
      "args": [
        "-y",
        "@playwright/mcp@latest"
      ]
    },

    "duckduckgo-search": {
      "command": "npx",
      "args": [
        "-y",
        "duckduckgo-mcp-server"
      ]
    }
  }
}
```

---

## 5️⃣ Run the Project

```bash
uv run app.py
```

---

# 💬 Example Prompts

```text
Search latest AI news
```

```text
Open github.com
```

```text
Search Python official website
```

```text
Take browser screenshot
```

---

# 🧩 How It Works

```text
User
 ↓
MCP Agent
 ↓
LLM Reasoning (Groq)
 ↓
MCP Client
 ↓
MCP Servers
 ↓
External Tools
 ↓
Final Response
```

---


# 🔒 Important Notes

* Do NOT upload your `.env` file to GitHub.
* Add `.env` to `.gitignore`.
* Some MCP tools may face API limits or robots.txt restrictions.

---

# 🌱 Future Improvements

* Add web-based frontend UI
* Integrate FastAPI backend
* Add more MCP servers
* Deploy online
* Add voice support
* Multi-agent workflows

---


# 👩‍💻 Author

**Nancy**


