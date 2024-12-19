# RAS Data Analysis

This repository contains a Jupyter Notebook focused on an initial analysis of CRM data to explore trends, data completeness, and understand key metrics. 

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Key Features of the Analysis](#key-features-of-the-analysis)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Next Steps](#next-steps)

---

## Project Overview
This is part one of a lareger project. The overall project goal is to create a “scorecard” methodology for weighing searches by category, by likelihood of leading to contract, by difficulty.
The first phase is to explore the data to gain an understanding of key variables and dependencies.
This project provides a detailed analysis of:
- Data completeness.
- Search for trends in searches and contracts over a five year timeframe.
- Insights into contract billing and hours reported.

---

## Dataset Description
The dataset includes:
- Searches created after January 1, 2020.
- Contract and billing information, including:
  - Division
  - Search Stage
  - Type of Case
  - Subject
  - Hours Reported
  - Dates related to search creation, contracts, billing, and completion.

---

## Key Features of the Analysis
- **Data Exploration**: Calculate missing values, unique values, and dataset completeness.
- **Time-Series Analysis**: Convert and analyze date columns to identify monthly and yearly trends.
- **Visualization**: Create scatter plots, line plots, bar charts, and histograms to explore patterns in contract billing and reported hours.
- **Filter and Grouping**: Filter data for specific criteria (e.g., completed contracts, hours > 0) and group by categories like subject, division, and date.

---

## Dependencies
The analysis uses the following Python libraries:
- `pandas` - For data manipulation and analysis.
- `seaborn` - For advanced data visualization.
- `matplotlib` - For creating static plots.
- `numpy` - For numerical operations.

---

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/RAS-Data-Analysis.git
   cd RAS-Data-Analysis
2. Install required libraries:
   ```bash
   pip install pandas seaborn matplotlib numpy
3. Place the CSV file containing the dataset:
   (all_searches_created_after_january_1_2020.csv) in the repository directory.
5. Run the jupyter notebook:
   ```bash
   jupyter notebook RAS_Data_Analysis.ipynb

---

## Visualizations
The notebook provides several visualizations, including:

- Scatter Plots: Displaying hours reported vs. billing dates.
- Bar Charts: Showing the distribution of searches, contracts, and hours reported by categories and months.
- Histograms: Analyzing contract durations and hours reported.
- Line Plots: Visualizing trends in hours reported over time.

---

## Next Steps
- Update the dataset with missing hours data from 2020 and 2021.
- Rerun the analysis to validate conclusions.
- Compare metrics across case types and subjects.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
The data used in this analysis was sourced from "Lyn's folder," generated on August 2, 2024. Special thanks to team members for their support in data collection and initial exploration.

---

Feel free to contribute, open issues, or suggest improvements!
