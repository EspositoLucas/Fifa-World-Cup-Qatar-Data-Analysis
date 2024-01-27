# Fifa World Cup Qatar Data Analysis

## Overview
This project focuses on conducting an Exploratory Data Analysis (EDA) of key metrics related to the FIFA World Cup Qatar 2022. The analysis covers various aspects such as the top scorer, teams with more possession, passing accuracy, goals, and goalkeepers with more unbeaten goals. The project utilizes Python for data analysis, Excel for data processing, and Power BI for creating an interactive dashboard.

## Project Structure
- **[notebooks](notebooks/):**
  - `player_analysis.ipynb`: Jupyter notebook containing EDA analysis of player-related metrics.
  - `goalkeeper_analysis.ipynb`: Jupyter notebook focusing on the EDA of goalkeeper-related metrics.
  - `web_scraping.ipynb`: Notebook dedicated to web scraping for collecting additional World Cup data.

- **[data](data/):**
  - All CSV files used for Power BI reporting are stored in this folder.
  - The dataset was sourced from Kaggle and includes comprehensive data on FIFA World Cup Qatar 2022.

- **Power BI Dashboard:**
  - `fifa_world_cup_2022_report.pbix`: Power BI file containing the interactive dashboard with visual representations of the analyzed data.

## How to Use
1. **Notebooks:**
    - Open and run the Jupyter notebooks in the specified order for a comprehensive analysis.
    - Ensure necessary Python libraries are installed; requirements are listed in each notebook.

2. **Data:**
    - All CSV files in the "data" folder are crucial for the Power BI dashboard.
    - Do not alter the folder structure to maintain data integrity.

3. **Power BI Dashboard:**
    - Open `FIFA_World_Cup_2022_Dashboard.pbix` using Power BI Desktop.
    - The dashboard provides an interactive interface for exploring the insights derived from the data.
    - You can also see the dashboard [here](https://app.powerbi.com/reportEmbed?reportId=6f4f8755-ba59-4f54-85fb-ac3b9b453710&autoAuth=true&ctid=a6fe1b1e-97b7-422d-b1bc-e37254398663)

## Acknowledgments
- Dataset: Obtained from [Kaggle](https://www.kaggle.com/datasets/tittobobby/fifa-world-cup-2022-player-stats)
- Libraries: Pandas, NumPy, Seaborn, Matplotlib for Python analysis
- Tools: Power BI for creating interactive visualizations
