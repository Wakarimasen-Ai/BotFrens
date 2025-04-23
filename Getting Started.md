# Getting Started

A quick guide to set up your local BotFrens development environment and start contributing.

---

## 1. Clone the Repository

```bash
git clone https://github.com/​_your_org_/BotFrens.git
cd BotFrens
```

---

## 2. Prerequisites

- **Docker** & **Docker Compose** installed  
- **VS Code** (optional, but recommended)  
  - Install the **Remote − Containers** extension  
- **Git** (latest version)  

---

## 3. Configure DevContainer (optional)

1. Open the project in VS Code.  
2. Click **Reopen in Container** when prompted.  
3. The devcontainer will build with:
   - Python 3.10  
   - Docker tools  
   - Pre-installed dependencies  

This yields a consistent environment for all contributors.

---

## 4. Environment Variables

1. Copy the example `.env.example` to `.env`:

   ```bash
   cp .env.example .env
   ```

2. Edit `.env` and fill in required values:
   - `OPENAI_API_KEY`  
   - `TELEGRAM_BOT_TOKEN`  
   - Any database credentials (PostgreSQL URL, etc.)

---

## 5. Install Dependencies

If you’re not using the devcontainer, run:

```bash
python3.10 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

---

## 6. Run the BotFrens System

1. **Start local services** (Postgres, vector DB, FastAPI server):

   ```bash
   docker-compose up -d
   ```

2. **Launch the orchestrator**:

   ```bash
   cd src
   python main.py
   ```

3. **Verify**: you should see log output indicating agents are ready.

---

## 7. Pick Your First Task

1. Visit the **BotFrens** Kanban board:  
   https://github.com/users/Wakarimasen-Ai/projects/1  
2. Select a task from **Ready** or **My Items** labeled **Volunteer Friendly**.  
3. Comment “I’m working on this” and assign yourself.  
4. Follow the task’s instructions, then open a Pull Request when done.

---

## 8. Run Tests

```bash
pytest
```

Make sure new changes pass existing tests or add new tests for your feature.

---

## 9. Need Help?

- Ask a question in **GitHub Discussions** or the project chat.  
- Reference the task card and any error output.  
- Someone (lead or fellow volunteer) will guide you.

---

You’re all set! Welcome aboard—let’s make BotFrens amazing together. 🎉  
```

> **Tip:** As you work through this guide, consider updating it if you spot unclear steps. Your contributions to documentation are just as valuable as code!