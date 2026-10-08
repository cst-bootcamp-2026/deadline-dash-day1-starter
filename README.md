# Deadline Dash -- Day 1 starter

The bare, untyped engine every student starts the bootcamp from -- four
seeded bugs, two of them already visible as failing tsets.

```bash
uv venv --python 3.12
source .venv/bin/activate     # Git Bash on Windows: source .venv/Scripts/activate
uv pip install -e ".[dev]"
pytest
python -m flappy.render_console   # or: python -m flappy
```
