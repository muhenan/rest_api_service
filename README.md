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
