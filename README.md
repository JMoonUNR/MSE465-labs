# MSE 465/665 Monte Carlo labs

Course files for the OpenMC labs in MSE 465/665 Fundamentals of Nuclear Power, University of Nevada, Reno.

## MC Lab B: Same problem, production code

Open the notebook in Google Colab:

https://colab.research.google.com/github/JMoonUNR/MSE465-labs/blob/main/labB/MSE465_MC_LabB_STUDENT.ipynb

Then use *File > Save a copy in Drive* and work only in your copy. The notebook's install cell downloads OpenMC and the nuclear data from the `labB` folder of this repository.

## If Colab does not work for you

This repository also runs in a GitHub Codespace, which comes with OpenMC already installed:

1. Sign in to GitHub, then on this page choose **Code > Codespaces > Create codespace on main**.
2. When the editor opens, open `labB/MSE465_MC_LabB_STUDENT.ipynb` and pick the Python kernel when asked.
3. Run the cells from the top. The install cell reports OpenMC as already installed and downloads only the nuclear data.

Stop the codespace when you finish (**Codespaces > Stop**). GitHub Free includes enough monthly compute hours for this lab.

## What is in `labB`

| Folder | Contents |
|---|---|
| `openmc/` | OpenMC 0.16.0 built for the Ubuntu 24.04 (`noble`) and 22.04 (`jammy`) images Colab uses, and the OpenMC Python package (wheel). OpenMC is open-source software (MIT license, openmc.org). |
| `data/` | Photon data for Pb, H and O, and neutron data for Pb-208, H-1 and O-16, from the ENDF/B-VII.1 library as converted for OpenMC (github.com/openmc-data-storage). |
