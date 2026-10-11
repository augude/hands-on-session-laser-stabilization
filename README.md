# Hands-on session: laser stabilization

Teaching materials for a practical session on laser-frequency stabilization. The notebooks use experimental data to explore cavity properties, PDH frequency calibration, feedback-loop bandwidth, frequency-noise density, and laser linewidth.

This session and material are designed by August Gude. The optical setup is designed and built by Francesco Marcolongo and described in his [semester thesis](litterature/Design%20and%20construction%20of%20a%20Pound-Drever-Hall%20locking%20setup%20for%20%20laser%20frequency%20stabilization%20to%20a%20reference%20multi-bore%20optical%20cavity.pdf).

## Repository layout

- `analysis/`
	- `analysis.ipynb`: student worksheet with guided exercises.
	- `analysis-filled-out.ipynb`: completed reference solution.
- `data/`
	- `cavity-properties/`: narrow and wide cavity transmission scans.
	- `frequency-noise/`: locked and unlocked PDH error-signal measurements.
	- `servo-bump/`: measurements taken with different P-gain settings.
- `litterature/`: reference material used in the notebooks, including the linewidth analyser manual.
- `pyproject.toml`: project metadata and Python dependencies.

## Getting started

The project requires Python 3.13 or newer. With [uv](https://docs.astral.sh/uv/) installed, create the project environment with:

```bash
uv sync
```

Open `analysis/analysis.ipynb` in VS Code or Jupyter and run the cells from the top. The notebook uses paths relative to the `analysis/` directory, so keep the notebook in its current location when running it.

Use `analysis-filled-out.ipynb` as the reference solution when needed.


