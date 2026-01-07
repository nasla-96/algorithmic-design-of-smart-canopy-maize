# Algorithmic Design of Smart-Canopy Maize

Code and example data for:
**"Towards smart canopies: Algorithmic design of maize canopy architectures that maximize light use efficiency"**

## Repository layout
- `notebooks/` : end-to-end notebook (geometry + GA + Helios)
- `configs/helios/` : Helios configuration files (portable paths)
- `data/example_inputs/` : small example inputs (optional)
- `data/example_outputs/` : small example outputs (fitness curves, summary CSVs)
- `results/` : local outputs (not version controlled)

## Environment
Create the conda environment:
`conda env create -f environment.yml`
Activate:
`conda activate nurbs`

## Quickstart (smoke test)
1. Create environment:
   - `conda env create -f environment.yml`
2. Activate:
   - `conda activate <ENV_NAME>`
3. Open and run:
   - `notebooks/GA_helios_cropped_120x24.ipynb`

## Notes
- Full simulation artifacts (large meshes/outputs) are not stored in Git.
- Helios must be installed separately and accessible on the system.