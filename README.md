# BotFrens

An **autonomous AI software development team**—a set of cooperating AI agents that can plan, code, test, deploy, and maintain projects end-to-end. BotFrens is designed to run on Python 3.10, leverage both local and OpenAI LLMs, and be orchestrated via a simple Kanban workflow.

---

## 📋 Table of Contents

1. [Features](#features)  
2. [Tech Stack](#tech-stack)  
3. [Repository Layout](#repository-layout)  
4. [Documentation](#documentation)  
5. [Getting Help & Communication](#getting-help--communication)  
6. [Contributing](#contributing)  
7. [License](#license)  

---

## 🚀 Features

- **Multi-agent orchestration** using PydanticAI & Logfire  
- **Hybrid LLM support**: Local inference (vLLM + Qwen/DeepSeek) and OpenAI API  
- **Tool integration** via Model Context Protocol (MCP) + FastAPI  
- **Containerized environment** with Docker & DevContainers  
- **CI/CD ready** with GitHub Actions / GitLab pipelines  
- **Vectorized knowledge base** using PostgreSQL + pgvector  
- **Volunteer-friendly workflow** backed by a GitHub Projects Kanban board  

---

## 🛠 Tech Stack

| Layer             | Technology                                    |
| ----------------- | --------------------------------------------- |
| Language & Orchestration | Python 3.10, PydanticAI, Logfire           |
| LLM Providers     | OpenAI API (GPT-4), vLLM (DeepSeek, Qwen-32B) |
| API Framework     | FastAPI                                        |
| Tool Protocol     | Model Context Protocol (MCP)                   |
| Containerization  | Docker, Docker Compose, VS Code DevContainer   |
| Storage & Search  | PostgreSQL, pgvector, HuggingFace SDK          |
| Version Control   | Git, GitHub + Projects (Kanban board)          |
| Notifications     | Telegram API (for human-in-loop alerts)        |

---

## 📖 Documentation

- **Architecture**: [docs/Implementation Plan/Architecture.md](docs/Implementation%20Plan/Architecture.md)  
- **Implementation Plan**: [docs/Implementation Plan/Implementation Plan.md](docs/Implementation%20Plan/Implementation%20Plan.md)  
- **Getting Started**: [Getting Started.md](Getting%20Started.md)  

---

## 💬 Getting Help & Communication

- **Kanban Board**: https://github.com/users/Wakarimasen-Ai/projects/1 – pick tasks from **Ready** or **My Items**  
- **Discussion & Chat**: <link to GitHub Discussions / Slack / Discord>  
- **Issue Tracker**: Please report bugs or ask questions via GitHub Issues.

---

## 🤝 Contributing

1. Read [Getting Started.md](Getting%20Started.md)  
2. Find a **“Volunteer Friendly”** or **“Good First Issue”** card on the Kanban board  
3. Fork the repo → create a branch → make your changes → open a Pull Request  
4. Wait for review (you’ll get feedback via PR comments)  
5. Celebrate 🎉  

See [.github/ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE/) for guidance on writing new task issues.

---

## 📄 License

This project is released under the [BSL License](LICENSE).  
Feel free to use and build upon BotFrens—contributions are always welcome!