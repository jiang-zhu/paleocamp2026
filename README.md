# An Introduction to Climate Modeling and Analysis

![paleoCAMP logo](./images/paleoCAMPLogo.png)

Teaching notebooks for the climate-modeling tutorials at [the 2026 paleoCAMP](https://paleoclimate.camp/) | June 15–June 29, 2026.
[Jiang Zhu](https://staff.cgd.ucar.edu/jiangzhu/) ([jiangzhu@ucar.edu](mailto:jiangzhu@ucar.edu)) · Climate & Global Dynamics Laboratory, NSF NCAR.

[![Jupyter Book](https://img.shields.io/badge/Jupyter%20Book-online-F37626?logo=jupyter&logoColor=white)](https://jiang-zhu.github.io/paleocamp2026/)

## Getting Started

Everything runs on NCAR [JupyterHub](https://jupyterhub.hpc.ucar.edu/) — no local setup needed.

1. Sign in to JupyterHub and start a Casper server (project `UAZN0052`).
2. Open a terminal and clone the repo:
   ```bash
   git clone https://github.com/jiang-zhu/paleocamp2026.git
   ```
3. Open a notebook and select the `NPL 2026a` kernel.

## Notebooks

**Prerequisites**
- `0.1_demo_unix.ipynb` — basic Unix/Linux commands
- `0.2_intro_jupyter.ipynb` — Python and Jupyter Notebooks
- `0.3_demo_ncar_account_jupyterhub.ipynb` — NSF NCAR computing, accounts, and JupyterHub access

**Main Learning Modules**
- `1_intro_to_CESM.ipynb` — CESM structure, components, and workflow
- `2_demo_run_CESM_4steps.ipynb` — configure, build, and submit a CESM run
- `3_analyze_CESM_output.ipynb` — analyze CESM output on JupyterHub
- `4a_opt1_run_piControl_midHolocene.ipynb` — Option 1: run and compare piControl and mid-Holocene
- `4b_opt2_analyze_long_midHolocene.ipynb` — Option 2: ITCZ and monsoon in a long mid-Holocene run

**Info and Advanced Modules**
- `5_info_Data_Access.ipynb` — accessing model output and data
- `6_info_iCESM_iTRACE.ipynb` — iCESM and iTRACE analysis
- `7_run_challenging_LGM.ipynb` — challenge: run a Last Glacial Maximum (LGM) simulation

## License

See [LICENSE](./LICENSE).

---

Developed for [paleoCAMP](https://paleoclimate.camp/) 2026 at NSF NCAR.
