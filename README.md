# NDR Backend - Decision Graph

This repository hosts the **live decision graph viewer** for the NDR Backend project.

## 🔗 View the Graph

**Live Graph:** https://kkrzeminski.github.io/ndr-decision-graph/

## What is this?

This graph visualizes the architectural decisions, implementation steps, and outcomes for the NDR Backend project using [Deciduous](https://github.com/deciduously/deciduous) - a decision graph tracking system.

## How it works

- The main NDR Backend repository is **private**
- This repository is **public** and contains only the graph viewer
- Graph data (`graph-data.json` and `git-history.json`) is automatically synced from the main repository
- The viewer is a static HTML page hosted via GitHub Pages

## Files

- `index.html` - Deciduous graph viewer (React app)
- `graph-data.json` - Decision nodes and edges
- `git-history.json` - Git commit history
- `.nojekyll` - Prevents Jekyll processing for GitHub Pages

## Privacy

This repository contains:
- ✅ Decision metadata (goals, actions, outcomes)
- ✅ Git commit messages and hashes
- ❌ No source code
- ❌ No sensitive data
- ❌ No credentials or configuration

---

**Main Project:** NDR Backend (private repository)
