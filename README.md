# Spatial sampling

University project on stratified two-stage cluster sampling of soil-chemistry data (Copper concentrations on Barro Colorado Island, Panama). Following the book [*Spatial Sampling with R* by Dick Brus](https://dickbrus.github.io/SpatialSamplingwithR/) — the book uses R, but I implemented the methods in Python.

## Code

- `main.py` — main sampling pipeline (KMeans + two-stage cluster sampling)
- `calculation_details.py` — sampling calculations
- `plot_cluster.py` — figure generation
- `main_manual_calculations.py` — manual verification of the sampling math
- `toy_dataset.py` — synthetic dataset for testing
- `soildata.csv` — input dataset
- Result figures at the top level: `cu_heatmap.pdf`, `selected_clusters*.pdf`, `soil_data_clustering.pdf`

## Paper

`paper/` contains the LaTeX writeup of the project (`main.tex`, `main_rev.tex` revision, `references.bib`, figures in `paper/img/`).
