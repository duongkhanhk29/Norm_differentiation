## Description

This repository contains the data and code used to replicate the results from the research on norm differentiation, based on the European Social Survey (Round 9). The core analysis code is provided in the **R Markdown** file **Fairness_sensitivity - final.RMD**, which can be used to reproduce the results of the study.

The repository includes the following files:

- **Fairness_sensitivity - final.RMD**: Main R Markdown file for replication.
- **ESS9_subset.csv**: Original and processed data file for analysis (which has been subsetted for chosen variables).
- **country.csv**: List of countries in the study
- **external.xlsx**: Cultural Tightness-Looseness Index for external validity checks 

The country names in the dataset are shortened for data visualization. For replication, ensure all data and code are in the same folder.

### Data and Code Availability Statement

This package uses data derived from the European Social Survey (Round 9). For full details on the database, please cite the following source:

**European Social Survey European Research Infrastructure (ESS ERIC) (2023) ESS9 - integrated file, edition 3.2 [Data set]. Sikt - Norwegian Agency for Shared Services in Education and Research. https://doi.org/10.21338/ess9e03_2.**

To replicate the research, download the necessary data and place it in the same directory as the provided R Markdown scripts. Ensure all required R packages, as listed in the script, are installed.

### Computational Requirements

- **Software**:
  - R (latest version recommended).
  - R Studio (for rendering the RMD files).
  - All necessary packages are specified in the script **Fairness_sensitivity - final.RMD**. Install them using the `install.packages()` function.

- **Hardware**:
  - Operating System: Any modern operating system (Windows, macOS, Linux).
  - CPU: Any recent multi-core processor should be sufficient.
  - Memory: Minimum 8GB RAM recommended.
  - Disk Space: At least 1GB free space for data and results.

- **Run Time**: The analysis typically takes **less than 5 minutes** depending on your hardware configuration.

### Instructions for Data Preparation and Analysis

1. **Data Preparation**:
   - Download the required dataset from the provided source (GDIM 2023).
   - Place all data and code files in the same directory.
   - Ensure that the data file is unzipped and ready for use.

2. **Analysis**:
   - Open the **Fairness_sensitivity - final.RMD** file in RStudio.
   - Follow the instructions within the script to load the data and execute the analysis.

Both R Markdown files are designed to run without manual intervention, but ensure all necessary packages are installed before beginning the analysis.

## License

![CC-BY-NC](assets/cc-by-nc.png) This repository is under a CC-BY-NC license. Usage by commercial entities is allowed, reselling it is not.
