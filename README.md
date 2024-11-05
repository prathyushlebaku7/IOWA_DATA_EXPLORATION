# 🗺️ Iowa Data Exploration

Welcome to the **Iowa Data Exploration** project! This repository contains an exploratory analysis of datasets from Iowa, focusing on statistical insights, geographic data integration, and other analytical techniques. Through Jupyter notebooks, the project demonstrates methods for understanding and visualizing data, with applications in mean comparisons, geographic data integration, and more.

## 📑 Table of Contents
- [✨ Features](#features)
- [📥 Installation](#installation)
- [🚀 Usage](#usage)
- [📂 Project Structure](#project-structure)
- [🔍 Examples](#examples)
- [🤝 Contributing](#contributing)
- [📜 License](#license)

## ✨ Features
- 📊 **Statistical Comparisons**: Compare means across different data categories.
- 🌍 **Geospatial Analysis**: Integrate Iowa’s geographic data using GeoPandas.
- 🔍 **Data Exploration**: Analyze crash data and other datasets to uncover insights.
- 📓 **Notebook Workflow**: Each analysis step is documented in Jupyter notebooks.

## 📥 Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/prathyushlebaku7/IOWA_DATA_EXPLORATION.git
    cd IOWA_DATA_EXPLORATION
    ```

2. **Set up the Environment**:
    It’s recommended to use a virtual environment. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
    *(Ensure that a `requirements.txt` file exists in the repository; if not, manually install packages like `pandas`, `geopandas`, `numpy`, and `matplotlib`.)*

3. **Install Jupyter Notebook**:
    If you haven’t installed Jupyter yet, you can do so with:
    ```bash
    pip install jupyter
    ```

## 🚀 Usage

1. **Run Jupyter Notebook**:
    Start the Jupyter Notebook server:
    ```bash
    jupyter notebook
    ```

2. **Open Notebooks**:
    - 📊 **Mean_Comparision.ipynb**: Compare means across different groups.
    - 🔎 **NB_code.ipynb**: Contains additional code for statistical analysis.
    - 🛣️ **fast_crash_integration.ipynb**: Analyzes crash data with geographic integration.

3. **Load Data**:
    Ensure all data files (e.g., `merged_csv_file_using_geopandas.csv`) are in the same directory as the notebooks for them to function correctly.

## 📂 Project Structure

- **Mean_Comparision.ipynb**: Notebook for comparing means across categories.
- **NB_code.ipynb**: Additional code for analysis and data processing.
- **fast_crash_integration.ipynb**: Focuses on integrating crash data with geographic information.
- **merged_csv_file_using_geopandas.csv**: CSV file with integrated geographic data.
- **README.md**: Project documentation.

## 🔍 Examples

Here’s an example of loading and exploring data in a notebook:

```python
import pandas as pd
import geopandas as gpd

# Load the data
data = pd.read_csv('merged_csv_file_using_geopandas.csv')

# Display the first few rows
data.head()
