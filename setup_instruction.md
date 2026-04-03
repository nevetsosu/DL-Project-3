# Project 3 — Environment Setup

## Setup with UV

**1. Install UV** (if you don't have it):

```bash
# macOS / Linux
curl -LsSf https://astral.sh/uv/install.sh | sh

# Windows (PowerShell)
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**2. Install dependencies:**

```bash
cd YOUR_PROJECT_DIRECTORY
uv sync
```

**3. Register the Jupyter kernel:**

```bash
uv run python -m ipykernel install --user --name project_III_Transformers --display-name "project_III_Transformers"
```

**4.** Open `project_III_Transformers.ipynb`, select the **"project_III_Transformers"** kernel, and start working.

> You are free to use your own Python, conda, or venv environment instead.
> Just make sure the packages listed in `pyproject.toml` are installed, along with `ipykernel`.

## Submission

Submit only your completed **`project_III_Transformers.ipynb`** notebook file.
