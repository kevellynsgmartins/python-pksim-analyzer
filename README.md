# PKSim Analyzer

## Overview

The **PKSim Analyzer** is a Python script designed to analyze and process pharmacokinetic (PK) simulation data in CSV format. It reads raw PK simulation data, applies filtering and unit conversion based on user-defined parameters, and generates processed results in Excel format (`.xlsx`). The tool also calculates and visualizes the Probability of Target Attainment (PTA) based on predefined thresholds.

The analysis is based on results obtained during the development of the scientific article _"Physiology-Based Pharmacokinetic Modeling for Prediction of Gentamicin Plasma Profile in Dogs with Renal Dysfunction."_ The dataset was exported from [PK-Sim](https://github.com/Open-Systems-Pharmacology/PK-Sim). More details on the methodology of the study can be found in the article.

## License - MIT

This software is provided as-is. There are no planned updates for the near future. You do not need to ask for permission to modify this script. However, if this script is used or altered, **proper credit and citation of the article must be given**.

## Features

The script provides customizable filtering, MIC (Minimum Inhibitory Concentration) calculations, and supports multiple types of analysis such as C<sub>max</sub>, AUC, and C<sub>trough</sub>. Unit conversion multipliers are also included.

- **CSV to Excel Conversion** – Converts raw CSV data to formatted Excel sheets.
- **Unit Conversion** – Automatically converts units (e.g., from µg/mL to mg/L).
- **MIC Calculation** – Calculates MIC values for multiple concentrations.
- **PTA Analysis** – Provides PTA analysis based on thresholds for different metrics.
- **Customizable Filters** – Supports flexible filtering based on user-defined parameters.
- **Excel Formatting** – Properly formats the resulting Excel file with multiple sheets for each parameter analysis.

## Requirements

Ensure the following Python libraries are installed:

- `pandas`
- `openpyxl`

You can install them using:

```bash
pip install -r requirements.txt
```

## End Notes
I would like to thank everyone who contributes to the tools and packages during the creation of this script, all authors cited, and also [@nicolasmartins23](https://github.com/nicolasmartins23) during the development stages of this script.
