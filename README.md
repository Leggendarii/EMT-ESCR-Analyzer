ESCR Analyzer Workspace
======================

Overview
--------
This workspace contains test cases for an ESCR (Estimator for Short-Circuit Residual) estimator. Open the workspace file `WS` to load the project and run the simulations.

Included test cases
-------------------
- A simple Thevenin network test case using a minimal setup to validate the ESCR estimator behavior.
- An IEEE 9-bus test case (`ieee_09_bus.pscx`) to validate the estimator on a standard benchmark network.

How to open
-----------
- Open the workspace file: WS (file: `WS.pswx`).

Running the tests
-----------------
1. Open the workspace `WS`.
2. Load the desired test case (`ieee_09_bus.pscx` or the Thevenin example).
3. Ensure the ESCR estimator block has its clock set to the block's right-hand side (set the estimator `Clock` parameter to `Right`).
4. Run the simulation to execute the test cases and collect results.

Files in this workspace
-----------------------
- `WS.pswx` — workspace file to open the project.
- `ieee_09_bus.pscx` — IEEE 9-bus test case.
- `ieee_09_bus_wIBR.pscx` — IEEE 9-bus test case with 2 IBRs
- `Tools.pslx` — supporting tools and scripts used by the workspace.

## Citation

If you use this repository or the associated data/code in your research, please cite:

```bibtex
@article{Darii_Estimation_of_Equivalent_2026,
  author = {Darii, Nicolae and Sharma, Ranjan and Mugambi, Germano Rugendo and Saborío-Romano, Oscar and Cutululis, Nicolaos A.},
  doi = {10.1016/j.epsr.2026.113491},
  journal = {Electric Power Systems Research},
  title = {{Estimation of Equivalent SCR for Offshore Wind}},
  url = {https://doi.org/10.1016/j.epsr.2026.113491},
  year = {2026}
}
