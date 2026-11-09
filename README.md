# Oldman River Dam - Sentinel-1 coregistered SLC stack (ISCE2)

Sentinel-1B descending track 71, IW2, VV, 144 dates (2017-02-26 to 2021-12-14), reference 2017-05-21.
Processed on ASF OpenSARlab: ISCE2 2.6.5 topsStack (slc workflow, NESD) -> MiaplPy load_data,
giving `slcStack.h5` (coregistered SLCs) and `geometryRadar.h5`.

**Data (slcStack.h5, geometryRadar.h5):** https://doi.org/10.5281/zenodo.24088874

| Notebook | What it does |
|---|---|
| `notebooks/00_Setup_oldman_isce2_environment` | builds the conda environment (`oldman_isce2_env.yml`, pinned versions) |
| `notebooks/01_Oldman_ISCE2_coregistered_SLC_stack` | bursts, orbits, DEM, ISCE2 topsStack, slcStack.h5 + geometryRadar.h5 |

The notebooks are saved with their printed outputs from the run.
`results/isce2/` holds the run's logs, ESD shifts, burst list, run files and quick-look figure.
