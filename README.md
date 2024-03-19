## Overview
This Jupyter Notebook contains Python code implementing Density-Based Spatial Clustering of Applications with Noise (DBSCAN) algorithm for clustering accident data in Central London. The notebook utilizes the UK accident dataset obtained from Kaggle and provides visualizations and analysis to identify accident hotspots and patterns.

### Files
- **DBSCAN.ipynb**: Jupyter Notebook containing the Python code for DBSCAN clustering
- **Visual Analytics Report.pdf**: Report providing a detailed analysis of UK road traffic accidents using spatiotemporal analysis
- **Visual Analytics.twb**: Tableau Workbook containing visualizations used in the analysis

### Usage
1. **DBSCAN.ipynb**: Open the notebook in a Jupyter environment
2. **Visual Analytics Report.pdf**: Refer to this report for a comprehensive analysis of UK accident data, including methodology, findings, and recommendations
3. **Visual Analytics.twb**: Open this Tableau Workbook to explore interactive visualizations of the UK accident data

### Contents
1. **Imports**: Libraries required for the analysis are imported
2. **Data Loading and Preprocessing**:
   - Accident data for the year 2014 within the City and Westminster boroughs is loaded and preprocessed
3. **DBSCAN Clustering**:
   - DBSCAN algorithm is applied to cluster accidents based on their geographical coordinates
   - Each cluster is assigned a unique color for visualization
4. **Visualization**:
   - The clustered accidents are visualized on a map using Folium
5. **Using Tableau Workbook**:
   - Open the **Visual Analytics.twb** file in Tableau to explore interactive visualizations such as temporal trends, spatial patterns, and accident hotspots
6. **Requirements**: Required libraries and installation instructions are provided
   
### Installation
To run the notebook, ensure you have all the required libraries installed. You can install them using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn folium
```
