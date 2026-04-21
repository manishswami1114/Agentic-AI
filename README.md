# Agentic-AI
A Repo contains multiple AI Agents 

## Overview
This repository contains a collection of multi‑agent pipelines, LangChain / LangGraph examples, and supporting notebooks for building AI‑augmented agents.

## Quick Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/manishswami1114/Agentic-AI.git
   cd Agentic-AI
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # macOS/Linux
   # .\venv\Scripts\activate  # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure environment variables**
   ```bash
   cp .env.example .env   # edit with your API keys, tokens, etc.
   ```
   The `.env` file is ignored by Git.

5. **Run notebooks or scripts**
   ```bash
   jupyter notebook          # open any `*.ipynb` in the `CrewAI` or `LanghChain` folders
   # or run a script directly
   python CrewAI/Agentic_sales_pipeline/Sales_Agent.ipynb
   ```

## Project Structure
```
Agentic-AI/
│
├─ CrewAI/                # Multi‑agent pipelines and example notebooks
├─ LangGraph/             # LangGraph demos and agents
├─ LanghChain/            # LangChain notebooks and utilities
├─ .gitignore             # Ignores .DS_Store and .env files
└─ README.md              # This file
```

## Contributing
1. Fork the repo.
2. Create a feature branch.
3. Commit your changes and push.
4. Open a Pull Request.

## License
MIT – see the `LICENSE` file for details.
