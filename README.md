# Hands-on session: laser stabilization

Teaching materials for a practical session on laser-frequency stabilization. The notebooks use experimental data to explore cavity properties, PDH frequency calibration, feedback-loop bandwidth, frequency-noise density, and laser linewidth.

## Repository layout

- `analysis/`
	- `analysis.ipynb`: student worksheet with guided exercises.
	- `analysis-filled-out.ipynb`: completed reference solution.
	- `analysis-student.ipynb`: alternate student worksheet.
- `data/`
	- `cavity-properties/`: narrow and wide cavity transmission scans.
	- `frequency-noise/`: locked and unlocked PDH error-signal measurements.
	- `servo-bump/`: measurements taken with different P-gain settings.
- `litterature/`: reference material used in the notebooks, including the linewidth analyser manual.
- `src/`: Python package source.
- `pyproject.toml`: project metadata and Python dependencies.

## Getting started

The project requires Python 3.13 or newer. With [uv](https://docs.astral.sh/uv/) installed, create the project environment with:

```bash
uv sync
```

Open `analysis/analysis.ipynb` in VS Code or Jupyter and run the cells from the top. The notebook uses paths relative to the `analysis/` directory, so keep the notebook in its current location when running it.

Use `analysis-filled-out.ipynb` as the reference solution when needed.
