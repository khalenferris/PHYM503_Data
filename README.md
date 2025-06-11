# PHYM503_Data
This repository contains all of the data, VULCAN configuration files, and figures used in the making of my PHYM503 Final Report on "Atmospheric Chemistry of Earth-Like Planets". Below is a description of each folder in the repository.

'PHYM503_Data/figures/' = All figures used in the report.

'PHYM503_Data/vul_data/' = The output of each simulation used in the report, in the standard .vul data format used by VULCAN.

'PHYM503_Data/vulcan_configs/' = The configuration file for each simulation used in the report. To reproduce any of the simulations in the report the config file can be placed in the VULCAN directory and renamed to 'vulcan_cfg.py', running 'vulcan.py' will then use this config file, and repeat the simulation. Note: additional changes to the VULCAN directory may be required depending on the simulation. E.g. to re-run an Archean Earth simulation one must ensure the necessary stellar flux, P-T-Kzz profile etc. files are in the correct directories. These file paths are declared at the beginning of the config file. 

'PHYM503_Data/stellar_flux/' = The stellar flux profiles used in each of the simulations. 

'PHYM503_Data/pt_kzz/' = The pressure-temperature, and Kzz (optional in VULCAN) profiles used in each of the simulations.
