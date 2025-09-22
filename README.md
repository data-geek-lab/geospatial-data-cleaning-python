# Data Cleaning for Geospatial Analysis in Python + Interactive Map

This repository contains the code, datasets, and tutorial notebook from my YouTube video:  
👉 Watch the full tutorial on YouTube: https://youtu.be/mFMenAad5vA

Pleae make sure to like and subscribe to my channel for more step-by-step tutorials. Thank you. 

In this project, we take a messy geospatial dataset (with missing coordinates, swapped lat/lon, inconsistent country codes, duplicates, and mixed formats) and clean it step by step in Python. Finally, we build an **interactive Folium map** with marker clusters and a heatmap.

---

## What's Inside
- **`geospatial_dirty_locations.csv`** → messy input dataset  
- **`country_lookup.csv`** → helper table to normalize country names and ISO codes  
- **`geospatial_cleaning_tutorial.ipynb`** → ready-to-run Jupyter Notebook with all cleaning steps  
- **`geospatial_cleaned.csv`** → cleaned dataset after running the notebook  
- **`geospatial_cleaned_map.html`** → interactive map export (open in any browser)  

---

## How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/DataGeekIsMyName/geospatial-data-cleaning-python.git
   cd geospatial-data-cleaning-python

## Packages you might need to install (only once, if you don't have them intalled already: 

pip install pandas numpy folium
pip install geopandas shapely fiona pyproj

## License

This project is for educational purposes. Datasets are synthetic and for demo use only.
You are free to fork, adapt, and use in your own projects with attribution.

Support My Work

Subscribe on YouTube → DataGeekIsMyName

☕ Buy Me a Coffee: https://buymeacoffee.com/datageekismyname
💎 Donate via PayPal: https://www.paypal.com/donate/?hosted_button_id=ZCL24X55R9C5G

Thank you for your support!
