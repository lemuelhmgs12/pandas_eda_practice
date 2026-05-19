# Pandas EDA Project

Exploratory Data Analysis using Python and pandas.

---

## Requirements

- Python 3.11+
- [uv](https://docs.astral.sh/uv/) (dependency manager)

---

## Setup

```bash
# Clone the repo
git clone <your-repo-url>
cd <project-folder>

# Install dependencies
uv sync
```

---

## Run

```bash
# Activate the virtual environment
source .venv/bin/activate        # Mac/Linux

# Launch Jupyter (or run your script)
uv run jupyter notebook
# or
uv run python your_script.py
```

---

## Project Structure

```
├── data/               # Raw and cleaned datasets
├── notebooks/          # Jupyter notebooks for EDA
├── src/                # Reusable Python scripts (if any)
├── pyproject.toml      # Dependencies managed by uv
└── README.md
```



