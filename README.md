# BFS & DFS | Interactive Uninformed Search

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ailabreport1.streamlit.app)
[![Tests](https://github.com/mokkerqin-hub/AI_LabReport1/actions/workflows/tests.yml/badge.svg)](https://github.com/mokkerqin-hub/AI_LabReport1/actions/workflows/tests.yml)

BSD3513 Introduction to Artificial Intelligence — Lab Report 1 · Mok Ker Qin · UMPSA

A Streamlit app that runs Breadth-First Search (BFS) and Depth-First Search (DFS) on a directed graph with alphabetical tie-breaking.

**Live app:** https://ailabreport1.streamlit.app

![App overview](screenshots/app_cover.png)

## Features
- Editable directed graph (Lab 1 graph by default)
- BFS and DFS step-by-step trace with graph visualisation
- Autoplay animation with adjustable speed
- BFS vs DFS comparison table
- Reset to default settings

| BFS search | DFS search |
|---|---|
| ![BFS](screenshots/app_bfs.png) | ![DFS](screenshots/app_dfs.png) |

| Autoplay (BFS in progress) | BFS vs DFS comparison |
|---|---|
| ![Autoplay](screenshots/app_bfs_autoplay.png) | ![Comparison](screenshots/app_comparison.png) |

## Run locally
```bash
git clone https://github.com/mokkerqin-hub/AI_LabReport1.git
cd AI_LabReport1
pip install -r requirements.txt
streamlit run bfsdfs.py
```

Run the tests with `pip install pytest` then `python -m pytest -q`.

## Project structure
```
bfsdfs.py            # Streamlit app
requirements.txt     # dependencies
tests/               # pytest unit tests
screenshots/         # README images
```

## Version
**v1.0** — BFS/DFS trace, autoplay, comparison table, reset button.
