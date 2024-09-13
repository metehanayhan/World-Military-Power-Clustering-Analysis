# World Military Power Clustering Analysis

## Project Objective
The goal of this project is to analyze the military capabilities of countries around the world and group them using clustering techniques. The analysis uses military and economic indicators such as air power, submarine fleets, defense budgets, and manpower to identify differences and similarities in the military capacities of various nations.

## Dataset
The dataset includes a comprehensive range of parameters that reflect the military and economic strengths of countries. Some of these parameters include:

- Air power
- Number of fighter jets
- Helicopter fleet
- Number of tanks
- Submarine fleet
- Defense spending
- Population
- Geographic factors such as land and sea borders

These parameters are used to better understand the military capacity of each country.

## Libraries Used
The following Python libraries were used in this project:

- `pandas`: For data manipulation and analysis
- `numpy`: For numerical computations
- `scikit-learn`: For machine learning models (K-Means)
- `yellowbrick`: For visualization and Elbow method
- `seaborn` and `matplotlib`: For data visualization
- `scipy`: For hierarchical clustering and dendrograms

## Project Steps

1. **Data Loading and Preprocessing**  
   - The dataset is loaded from an Excel file.
   - Missing values are cleaned, and relevant columns are selected for the analysis.

2. **Data Normalization**  
   - `StandardScaler` is used to normalize the data, ensuring all features are on the same scale.

3. **Clustering Analysis**  
   - The `K-Means` algorithm is applied for clustering analysis.
   - The Elbow method is used to determine the optimal number of clusters.

4. **Results Visualization**  
   - The distribution of countries within clusters is visualized and analyzed.
   - A dendrogram is created for hierarchical clustering.

## Results
The project groups countries into clusters based on their military capacities. These clusters provide insights into the global military balance and enable deeper analysis of the defense capabilities of different nations.