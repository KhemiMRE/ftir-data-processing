# FTIR Data Processing

This repository contains a Jupyter notebook implementing a reproducible framework for processing Fourier Transform Infrared (FTIR) spectral data using slope-based variable selection and multivariate analysis.

## Features

- **Slope-Based Variable Selection:** Identifies the most dynamic wavenumbers by calculating the slope of absorbance changes across time or experimental conditions.
- **Multivariate Analysis:** Uses Principal Component Analysis (PCA) and K-means clustering for dimensionality reduction and grouping of spectral patterns.
- **Broad Dataset Compatibility:** While originally developed for analyzing the thermal degradation of vegetable oils, this method is applicable to other FTIR datasets, including polymers, lubricants, and pigments.

## Applications

- Monitoring thermal or chemical degradation
- Feature selection for spectroscopic data
- Time-series analysis in spectroscopy
- Spectral clustering and classification

## Installation

Install required Python packages using:

```bash
pip install -r requirements.txt
```

## Usage

Open the notebook and run the cells sequentially. It includes data preprocessing, slope calculation, and multivariate analysis steps.

```bash
jupyter notebook ftir_analysis_notebook.ipynb
```

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**. See the [LICENSE](LICENSE) file for more information.
