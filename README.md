# 🎲 Simulation Challenge

## Quick Start

1. **Fork** this repository to your GitHub account: [https://github.com/flyaflya/simulationChallenge](https://github.com/flyaflya/simulationChallenge)
2. **Clone** your forked repo locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/simulationChallenge.git
   ```
3. **Set up Python environment** (see below)
4. Open in Cursor and complete the analysis in `index.qmd`
5. Render to HTML and push to GitHub
6. Enable GitHub Pages and view at: `https://YOUR-USERNAME.github.io/simulationChallenge/`

## Environment Setup

This project uses a Python virtual environment (`.venv`) to manage dependencies.

**Initial setup:**
```bash
# Create virtual environment (if it doesn't exist)
python3 -m venv .venv

# Activate the virtual environment
source .venv/bin/activate  # On macOS/Linux
# OR
.venv\Scripts\activate      # On Windows

# Install all required packages
pip install -r requirements.txt
```

**Why packages don't persist without `.venv`:**
- Without a virtual environment, packages get installed to system Python or user site-packages
- Quarto might use a different Python interpreter than where packages were installed
- The `.venv` ensures Quarto and your code use the same Python with all dependencies

**If you need to reinstall packages:**
```bash
source .venv/bin/activate  # Activate first!
pip install -r requirements.txt
```

## See the Github Page of This Challenge for Copy/Paste & Reference

`https://flyaflya.github.io/simulationChallenge/`

---
*Replace YOUR-USERNAME with your actual GitHub username*