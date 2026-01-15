![Image](https://github.com/user-attachments/assets/38e2c74b-8172-4db8-b9a5-8726604df10f)

# Streamlit CSV Cleaner

## Overview
This program creates an interactive CSV cleaning tool built with streamlit, pandas, and plotly to allow the user to upload and preview a CSV file, analyze null values, visualize missing data, apply a wide range of cleaning operations, and then finally download that cleaned data without having to write any code.

## Current Features
- Upload and preview CSV files
- Displays first 8 rows of data
- Data description summary
- Data Statistics:
    - Numerical null counts
    - Text null counts
    - Total null values
    - Duplicate row count
    - Row and column counts
- Visualizations:
    - Null values by column (bar chart)
    - Missing vs filled values by column (stacked bar chart)
- Data cleaning options:
    - Numeric column cleaning with custom value support
    - Text column cleaning with custom input support
    - Text formatting 
    - Drop duplicate rows
    - Drop rows or columns containing null values
- Preview of cleaned data
- Download cleaned CSV
- Reset cleaned dataset to original dataset
- Sample dataset for demo

## Planned features
- Column-specific cleaning controls
- Improved UI layout and styling
- Additional data validation and profiling

## How to run app
- 1. Clone the repository
- 2. Install dependencies
    - pip install -r requirements.txt
- 3. Run the Streamlit app
    - streamlit run csv_cleaner_app.py

## Notes
- Requires Python 3.9+
- All dependencies are listed in `requirements.txt`
- The app opens automatically in your browser




