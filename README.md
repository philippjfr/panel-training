# Panel Training

Training materials and notebooks for learning Panel, Param, and `panel-material-ui`.

## Requirements

- Python `3.13`
- One environment manager:
  - `uv`, or
  - `pixi`

## Option 1: Setup with uv

This project already includes a `pyproject.toml` with dependencies.

```bash
uv sync
```

Then start JupyterLab:

```bash
uv run jupyter lab
```

## Option 2: Setup with pixi

This project includes a `pixi.toml`.

```bash
pixi install
```

Then start JupyterLab:

```bash
pixi run lab
```

## Notes

- Notebook data file expected by multiple tutorials: `windturbines.parq`
- If your Jupyter kernel does not appear, restart JupyterLab after environment setup.
