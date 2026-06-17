# The-Jupiter-project

One-line tagline
A reproducible Jupyter notebook that simulates a Jupiter gravitational signal embedded in noisy neural population activity and demonstrates a recovered “Jupiter-shaped” signal (correlation = 0.854).

## What this project is

This repo contains `Jupiter_Project_1.ipynb` — a self-contained experiment that:

1. Simulates gravitational-like input patterns (Jupiter signal) injected into a neural population model.
2. Adds biologically plausible noise and runs signal-recovery algorithms.
3. Reports a recovered signal with correlation ≈ 0.854 and visualizations.

## Why it matters

This is an exploratory investigation into whether distant planetary-like periodic inputs could be detectable in simulated neural population data. The notebook demonstrates simulation code, analysis, and plotting so others can reproduce and extend the experiment.

## Quickstart — run in <5 minutes

**Option A — Run in Colab (recommended)**

1. Open this notebook in Colab: https://colab.research.google.com/github/victoriamvance-commits/The-Jupiter-project/blob/main/Jupiter_Project_1.ipynb
2. Runtime → Change runtime type if GPU/TPU is desired (not required).
3. Run all cells.

**Option B — Run locally**

1. Clone:

   git clone https://github.com/victoriamvance-commits/The-Jupiter-project.git
2. Create environment and install dependencies:

   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
3. Open `Jupiter_Project_1.ipynb` with Jupyter Notebook or JupyterLab:

   jupyter lab

## Reproducibility

- See `requirements.txt` for package dependencies.
- Random seeds and key parameters are defined at the top of the notebook.

## Results

- The notebook recovers a “Jupiter-shaped” signal in simulated neurons with a reported Pearson correlation ≈ 0.854 (see Results section / the final plotting cell).

## How to contribute

- Open issues for reproducibility requests or improvements.
- Add tests or a script-based conversion (e.g., `scripts/run_experiment.py`) to automate runs.
- Consider adding real data comparison scripts if you have biological datasets.

## License

This project is released under the MIT License — see `LICENSE`.

## Contact / Author

victoriamvance-commits — https://github.com/victoriamvance-commits
