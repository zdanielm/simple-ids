# Simple IDS

## A simple intrusion detection system (IDS) written in Python.

### [Based on How to Build a Real-Time Intrusion Detection System with Python and Open-Source Libraries - FreeCodeCamp](https://www.freecodecamp.org/news/build-a-real-time-intrusion-detection-system-with-python/)


## Installation & Setup

### 1. Prerequisites

Install [uv](https://docs.astral.sh/uv/getting-started/installation/).

### 2. Clone the repository

```bash
git clone https://github.com/zdanielm/simple-ids.git
cd simple-ids
```

### 3. Install dependencies

```bash
uv sync
```

This automatically creates a virtual environment (`.venv`) and installs all dependencies specified in `pyproject.toml` using `uv.lock`.

### 4. Run the application

```bash
uv run simple-ids
```

Alternatively, run the main Python file directly:

```bash
uv run main.py
```

### Updating dependencies

To synchronize your environment with the project's dependencies:

```bash
uv sync
```

## Planned Upgrades

- Integrating [Cloudflare's Clef](https://openrouter.ai/cloudflare/clef) or [Clef Flash](https://openrouter.ai/cloudflare/clef-flash)
    - Creating a logic of when a Clef opinion is needed, and when is the local Sklearn enough
