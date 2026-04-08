# Custom GPT

A go at making my own GPT from scratch. Doing so to learn how many llm actually work.

## Overview

---

## Dataset


---

## Approach

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| PyTorch | Model training and fine-tuning |
| NumPy | Data manipulation |
| tqdm | Training progress tracking |
| urllib | Handling URL requests (mainly to download dataset) |
| Matplotlib | Plotting Graphs |

---

## Project Structure

```
├── custom_gpt.ipynb           # Main training and evaluation notebook
├── tinyshakespeare.txt        # Dataset
├── code_snippets/             # Utility scripts (if needed)
├── requirement.txt            # Dependencies
├── pyproject.toml             # uv project toml file
```

---

## Installation

```bash
pip install uv
uv venv ./.venv --python 3.11
uv sync
```

---

## Notes

This was an exploratory research project comparing pretrained CNN architectures on a real-world medical imaging dataset. The goal was to understand how well off-the-shelf vision models transfer to neonatal jaundice classification.