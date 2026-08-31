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

## Related Thesis

This repository implements methods developed in the PhD thesis:

> Marcos Escobar, K. (2026). *Study of vegetable oil degradation using optical techniques and artificial intelligence algorithms* [Doctoral thesis, Instituto Politécnico Nacional, CICATA Unidad Querétaro].

The full text is available in [docs/Marcos-Escobar_2026_PhD-Thesis_FTIR-Vegetable-Oil-Degradation.pdf](docs/Marcos-Escobar_2026_PhD-Thesis_FTIR-Vegetable-Oil-Degradation.pdf).

**Abstract:** Thermal degradation of vegetable oils is a critical issue in both the food industry and domestic applications, as it directly affects nutritional quality, sensory properties, and product safety. This thesis proposes and validates a slope-based framework for objective feature extraction from FTIR spectra, quantifying systematic absorbance changes at each wavenumber via linear regression to identify the most dynamically relevant wavenumbers. Applied to the thermal degradation of soybean oil (ATR-FTIR and UV-Vis, supported by iodine value and specific extinction coefficient measurements), the selected wavenumbers are used for unsupervised multivariate analysis (PCA, k-means clustering) and to train machine learning models predicting iodine value directly from spectral data. The results show that this reduced-feature approach improves interpretability, reproducibility, and computational efficiency over conventional band- or region-based strategies.

*Note: per the institutional authorization on file, reproduction of the thesis's text, figures, or data requires permission from the author and thesis directors; any authorized use should credit and cite the thesis above.*

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**. See the [LICENSE](LICENSE) file for more information.
