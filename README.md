# Oldman River Dam - Sentinel-1 coregistered SLC stack (ISCE2) and SARvey

Sentinel-1B descending track 71, IW2, VV, 144 dates (2017-02-26 to 2021-12-14), reference 2017-05-21.
Processed on ASF OpenSARlab: ISCE2 2.6.5 topsStack (slc workflow, NESD) -> MiaplPy load_data -> SARvey 1.3.0.

**Data (slcStack.h5, geometryRadar.h5):** https://doi.org/10.5281/zenodo.24088874

| Notebook | What it does |
|---|---|
| 00_Setup_oldman_isce2_environment | builds the conda environment (pinned versions) |
| 00b_Setup_SARvey | adds SARvey to the environment |
| 01_Oldman_ISCE2_coregistered_SLC_stack | bursts, orbits, DEM, ISCE2 topsStack, slcStack.h5 + geometryRadar.h5 |
| 02_Oldman_SARvey | SARvey steps 0-4, maps and GeoPackage export |

The notebooks are saved with their printed outputs from the run.
