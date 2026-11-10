# Week 6 starter

Practice repository for **Week 6: Instrumental Variables**.
Full instructions: <https://yoonismo.github.io/causal-computing/week6.html>

## What is in here

| File | Purpose |
|---|---|
| `week6.ipynb` | The code from the Week 6 page, in the same order |
| `requirements.txt` | The packages the automatic check installs |
| `.github/workflows/ci.yml` | The automatic check: runs the notebook on GitHub's computer after every push |

## Before you start

Week 6 also uses `linearmodels` (for 2SLS with correct standard errors). Activate the course environment and install the packages (this works from any folder; the ones you already have are skipped):

```bash
source ~/ECON481/.venv/bin/activate      # macOS
~\ECON481\.venv\Scripts\activate          # Windows (PowerShell)
uv pip install pandas causaldata statsmodels matplotlib linearmodels
```

Run only the `activate` line for your system.

The data come with the `causaldata` package, so you need an internet connection only to install the packages.

## Steps

1. Click **Use this template** → **Create a new repository**, then clone your copy to your computer, as in Week 1 Lab 3.
2. Run `week6.ipynb` in order along with the Week 6 page, and answer the questions in it.
3. Clear all outputs, then `git add`, `git commit` and `git push`. The **Actions** tab should turn green.
