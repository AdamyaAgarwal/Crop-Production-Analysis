# Crop-Production-Analysis
A data visualization project to visualize annual crop production in India using Python, we have also used Plotly and Streamlit to create an interactive web application to visualize seasonal crop patterns in various zones in India.

## Data
We have used the following datasets for our analysis

  1) India's 1998-2017 crop production statistics by state and district showing annual production of more than fifty crops
  2) Rainfall statistics of India from 1998 to 2017, categorised by district, state and sub-division
  3) India district-wise geojson (epsg:4326) created from India shape-file using QGIS software.

## Tasks
We have implemented the following tasks in our dashboard:

Task 1: To analyze crop production statistics across the nation (district-wise)
Task 2: To analyze trends in crop production over the years
Task 3: To correlate rainfall pattern with crop production trends     

## Execution commands
For installing the dependencies, use:
`pip install requirements.txt`
Please unzip the file `merged.zip` to get `merged.csv` file before executing the script
For executing the script and hosting the dashboard locally, use:
`streamlit run final.py`
