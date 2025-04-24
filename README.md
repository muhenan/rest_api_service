# REST API Service with FastAPI & uv

A minimal Python REST API project using [FastAPI](https://fastapi.tiangolo.com/) and managed entirely by [uv](https://github.com/astral-sh/uv).

## 🚀 Quick Start

```bash
# Clone the project
git clone <your-repo-url>
cd rest_api_service

# Install dependencies from uv.lock
uv sync

# Run the service
uv run uvicorn main:app --reload
```

## 🔧 Project Structure
```bash
rest_api_service/
├── main.py         # Entry point for FastAPI app
├── uv.toml         # Dependency declarations (managed by uv)
├── uv.lock         # Locked dependencies
└── .env            # (Optional) Environment variables
```

## 📦 Dependency Management with uv
This project uses uv for Python dependency and virtual environment management:

```bash
# Initialize the project with uv
uv init

# Add dependencies
uv add fastapi uvicorn[standard] python-dotenv

# Run scripts from uv's virtual environment
uv run uvicorn main:app --reload
```
No pip, no venv, no requirements.txt — everything is handled by uv.

## 🧪 Example
* GET / → returns { "message": "Hello, uv!" }