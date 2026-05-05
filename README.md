# Air-Quality-Behavioral-Health-Visualization


Exploring the relationship between environmental factors and public health using interactive data visualizations.

Project Report:

 Overview

This project analyzes how air quality impacts behavioral health outcomes such as physical activity and obesity rates across the United States.

By combining datasets from the CDC (BRFSS) and EPA, we uncover spatial and temporal patterns that highlight how environmental conditions influence public health trends.

 Objectives
Analyze correlations between air pollution and health indicators
Identify regional trends across the U.S.
Explore demographic disparities in health outcomes
Build an interactive visualization dashboard using D3.js
 Datasets
1. Behavioral Health Data (CDC - BRFSS)
Covers: 2011–2023
Includes:
Obesity rates
Physical activity levels
Demographics (age, income, race, education)
Preprocessing:
Filter relevant indicators
Normalize categories
Aggregate by state & year
2. Air Quality Data (EPA)
Covers: 2010–2023
Includes:
PM2.5, NO₂ levels
Preprocessing:
Extract year
Standardize locations
Handle missing values
Aggregate by state & year
🧹 Data Processing Pipeline
Raw Data → Cleaning → Aggregation → Merging → Analysis → Visualization

Steps:

Handle missing values (mean imputation / state averages)
Align datasets by state + year
Merge datasets for unified analysis
Create regional groupings (optional)
 Visualizations (D3.js)
 Choropleth Map
Displays obesity rates + pollution levels
Interactive filters:
Year
Pollutant type
 Time Series Line Chart
Tracks trends over time:
Obesity vs PM2.5 / NO₂
Region-wise comparisons
 Scatter Plot
X-axis: Pollution
Y-axis: Obesity / Physical Activity
Color: State / Demographic group
 Demographic Bar Chart
Compares obesity across:
Income
Education
Race
Split by pollution levels
 Dashboard
Integrated layout:
Map (left)
Line chart (top-right)
Scatter plot (bottom-right)
Global filters for interaction

 The wireframes (pages 6–8) show the full dashboard layout and interaction design.

 Key Insights (Expected)
Poor air quality may correlate with:
Lower physical activity
Higher obesity rates
Certain demographics are more affected
Regional clusters reveal environmental health disparities
 Tech Stack
Visualization: D3.js
Data Processing: Python (Pandas, NumPy)
Development: Jupyter Notebook, VS Code
Version Control: Git & GitHub
 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/air-quality-health-viz.git
cd air-quality-health-viz
2. Install Dependencies
pip install pandas numpy
3. Run Data Processing
python preprocess.py
4. Launch Visualization

Open:

index.html

in your browser
