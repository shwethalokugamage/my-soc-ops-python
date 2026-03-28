# 🎉 Soc Ops — Social Bingo

> **Break the ice. Spark connections. Get five in a row.**

Soc Ops is a **social bingo game** built for in-person mixers, team events, and workshops. Each player gets a unique 5×5 bingo board filled with fun prompts like *"has lived in another country"* or *"can juggle"*. Mingle, ask questions, mark your matches — first to BINGO wins!

Built with **FastAPI**, **HTMX**, and **Jinja2** — no page reloads, real-time board updates, and zero JavaScript frameworks.

---

## ✨ Features

- 🎲 **Randomised boards** — every player gets a unique card, so no two games are the same
- 🆓 **Free space** — the centre square is always pre-marked to get things rolling
- ✅ **Instant BINGO detection** — rows, columns, and diagonals are all checked automatically
- 🔄 **One-click reset** — start a fresh game in seconds
- 📱 **Mobile-friendly** — plays beautifully on any screen size
- ⚡ **HTMX-powered** — snappy updates without a heavy frontend framework

---

## 🚀 Getting Started

### Prerequisites

- Python 3.13+
- [uv](https://docs.astral.sh/uv/) (recommended) or pip

### Run locally

```bash
# Install dependencies
uv sync

# Start the server
uv run soc-ops
```

Then open **http://localhost:8000** in your browser and share the link with your team!

### Run with pip

```bash
pip install -e .
soc-ops
```

---

## 🛠️ Development

```bash
# Install dev dependencies
uv sync --group dev

# Lint & format
uv run ruff check .
uv run ruff format .

# Run tests
uv run pytest
```

---

## 📚 Lab Guide

This project is used as the hands-on example in the **GitHub Copilot Dev Days** agent lab. Follow the parts below to go from zero to a fully AI-assisted Python app.

| Part | Title |
|------|-------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Overview & Checklist |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Setup & Context Engineering |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Design-First Frontend |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | [FastAPI](https://fastapi.tiangolo.com/) |
| Templating | [Jinja2](https://jinja.palletsprojects.com/) |
| Interactivity | [HTMX](https://htmx.org/) |
| Linting | [Ruff](https://docs.astral.sh/ruff/) |
| Testing | [pytest](https://pytest.org/) |
| Sessions | [Starlette SessionMiddleware](https://www.starlette.io/middleware/) |

---

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

---

## 📄 License

This project is licensed under the terms in [LICENSE](LICENSE).
