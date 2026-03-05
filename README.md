# Boone County Farmland Change Analysis

This repository contains a geospatial analysis project that investigates the transformation and reduction of farmland in Boone County over a 10-year period.

## Features
- **Data Engineering:** Extracts and processes multi-temporal geographic data using `geopandas` and `rasterio`.
- **Longitudinal Study:** Compares historical land-use patterns to quantify agricultural changes and urban development indicators.
- **Production-Ready Script:** The core analytical pipeline has been extracted from its original Jupyter Notebook format into a clean, PEP8-compliant Python executable (`Final_Project_Geospatial farmland story.py`).

## Setup & Installation

It is recommended to use a virtual environment to manage dependencies.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/boakyejeff/Farmland.git
   cd Farmland
   ```
2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```
3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Execute the analysis:**
   ```bash
   python "Final_Project_Geospatial farmland story.py"
   ```

## Dependencies Highlights
Core geospatial libraries employed in this project:
- `geopandas`
- `rasterio`
- `matplotlib`
- `numpy`

## License
MIT License.
