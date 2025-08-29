# PKSim Analyzer

## Overview

The **PKSim Analyzer** is a Python script designed to analyze and process pharmacokinetic (PK) simulation data in CSV format. It reads raw PK simulation data, applies filtering and unit conversion based on user-defined parameters, and then generates processed results in Excel format (.xlsx). The tool also calculates and visualizes the Probability of Target Attainment (PTA) based on predefined thresholds.

The analysis is based on results obtained during the development of the scientific article "Physiology-Based Pharmacokinetic Modeling for Prediction of Gentamicin
Plasma Profile in Dogs with Renal Dysfunction". The dataset was exported from (PKSim)[https://github.com/Open-Systems-Pharmacology/PK-Sim]. More details on the methodology of the study can be found in the article

## License - MIT
This software is provided as-is. There are no planned updates for the near future, you do not need to ask for permission to change this script, but, if this script is used or altered, creditation and citation of the article must be given.

## Features

The script provides customizable filtering, MIC (Minimum Inhibitory Concentration) calculations, and supports multiple types of analysis such as C_max, AUC, and C_trough. There are multipliers that can be used to convert units as well.

- **CSV to Excel Conversion**: Converts raw CSV data to formatted Excel sheets.
- **Unit Conversion**: Supports automatic conversion of units (e.g., from µg/ml to mg/L).
- **MIC Calculation**: Calculates MIC values for multiple concentrations.
- **PTA Analysis**: Provides PTA analysis based on thresholds for different metrics.
- **Customizable Filters**: Supports flexible filtering based on user-defined parameters.
- **Excel Formatting**: Properly formats the resulting Excel file with multiple sheets for each parameter analysis.

## Requirements

To use this script, ensure you have the following Python libraries installed:

- `pandas`
- `openpyxl`

You can install them using pip:

```bash
pip install -r requirements.txt

## End Notes
I would like to thank everyone who contributes to the tools and packages during the creation of this script, all authors cited, and also @nicolasmartins23 during the development stages of this script.
