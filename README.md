# MLB Pitcher Clustering
This project analyzes MLB pitchers using clustering techniques to identify distinct groups based on their performance metrics for the 2023 season.
## Complimentary Medium Post
Here is a link to my Medium post describing my processes and the insights that can be drawn from it: <br /> 
https://medium.com/inst414-data-science-tech/comparing-mlb-pitchers-using-underlying-metrics-8a8f792e3999

## Repository Structure
### clustering.ipynb: Jupyter notebook containing the clustering analysis code.
### fangraphs_season_level.csv: Dataset with performance metrics for the analysis.

## Getting Started
## Prerequisites
- Python 3.6+
- pandas
- scikit-learn
- matplotlib
- seaborn
- gap_statistic

## Setup
1. Clone this repository to your local machine.
2. Ensure Python 3.6+ is installed on your system.
3. Install Pandas, sci-kit-learn, Matplotlib, seaborn, and gap_statistic using pip:
## Data Preparation and Analysis
- Filter pitchers who played in 2023 and pitched at least 25 innings.
- Scale performance metrics using MinMaxScaler.
- Determine the optimal number of clusters using the Elbow method and Gap statistic.
- Perform KMeans clustering and visualize results with scatter plots.
