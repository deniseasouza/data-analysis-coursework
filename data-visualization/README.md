# AI Impact on Jobs by 2030 — Data Visualization

Visual study of a 3,000-row dataset describing how exposed different jobs are to AI by 2030.

## Dataset

`data/raw/ai_impact_on_jobs_2030.csv` — 3,000 records, 20 columns per job record:

- **Job context:** title, industry, country, education level, years of experience, company size
- **AI exposure:** replacement risk (0–1), automation level, AI tool usage, required skills
- **Outlook:** future demand score, projected job growth by 2030, hiring trend for 2026, remote-work possibility
- **Conditions:** average salary (USD), weekly hours, performance score, upskilling needed, job satisfaction

## What was done

`notebooks/01_data_profiling.ipynb` runs an automated profiling pass with **ydata-profiling**, producing distributions, correlations, missing-value and duplicate diagnostics for every column — the exploratory base for the charts discussed in the report.

The full analysis, chart choices and conclusions are in [`report/data-visualization-report.pdf`](report/data-visualization-report.pdf).

## Tech stack

`Python` · `pandas` · `ydata-profiling` · `Jupyter`

## How to run

```bash
pip install pandas ydata-profiling ipywidgets jupyterlab
jupyter lab notebooks/01_data_profiling.ipynb
```

Notebook outputs were cleared before committing — the embedded profiling report weighed 6.5 MB. Re-run the notebook to regenerate it.
