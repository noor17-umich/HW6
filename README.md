## HW6
# HW6 - Data Visualization and World Cup Analysis

This repository contains the solution for **Homework 6**. It includes tasks related to **Data Visualization** using R and **Python programming** for analyzing World Cup data.

## Repository Structure

- **`Copy_of_HW6.ipynb`**: Python notebook created using Google Colab. This file processes the World Cup match data, calculates the number of matches played between teams, and calculates the total goals scored by each home team.
- **`HW6_Data_Visualization.html`**: The output HTML generated from an R Markdown file. It contains visualizations of house price trends and unemployment percentages over the years.
- **`HW6_Data_Visualization.rmd`**: The R Markdown file containing the code for visualizing the house price index and unemployment percentage over time.
- **`HW6_WorldCupAnalysis.py`**: Python script used for analyzing the World Cup data. It calculates match counts and total goals for home teams.
- **`team_pairs.csv`**: CSV file containing the pairwise match statistics, including match counts (`weight`) and total goals scored by the home teams (`HomeGoalTotal`).
- **`team_pairs.csv.png`**: Screenshot of the `team_pairs.csv` file for visualization.

## Task Breakdown

### **1. Data Visualization in R**
- Created line plots representing the trend of house prices over time for each state using `facet_wrap`.
- Used `gather()` to reshape the data, focusing on house price indices and unemployment percentages.
- Plotted both house price index and unemployment percentages on the same chart for comparison.
- Generated an HTML report using R Markdown containing the charts and analysis.

### **2. World Cup Analysis in Python**
- Loaded the `WorldCupMatches.csv` file and performed data analysis using pandas.
- Grouped the data by **Home Team Initials** and **Away Team Initials** to find how many times these countries' teams played a match.
- Calculated the total goals scored by each **home team**.
- Created a `team_pairs` dataframe containing the number of matches played (`weight`) and total goals scored by the home teams (`HomeGoalTotal`).
- Saved the `team_pairs` dataframe as a CSV file (`team_pairs.csv`).

### **3. Cytoscape Network Visualization**
- Imported the `team_pairs.csv` file into **Cytoscape** to create a network.
- Colored the **nodes** based on `HomeGoalTotal`.
- Adjusted the **edges** using the `weight` column to indicate how often teams played against each other.
- Applied the **yFiles Organic Layout** to the network.
- Added a title annotation to the network and exported the image.

## Google Colab Link
You can view and run the Python notebook on Google Colab here:

[**HW6 Python Notebook**](https://colab.research.google.com/drive/1Uy9CCJT9Z0SAvQ8HgiicCK3IFHJTOoRs?usp=sharing)

## How to Use
1. Clone this repository or download the files.
2. Open `Copy_of_HW6.ipynb` in Google Colab or a local Jupyter environment to view and run the Python code.
3. Open `HW6_Data_Visualization.rmd` in RStudio to generate the HTML report with visualizations.

## Contact
For any questions or issues, please feel free to reach out.

---

**Note**: Make sure all required files like `WorldCupMatches.csv` and `house_prices.rda` are present in the same working directory or adjust the paths in your code.
