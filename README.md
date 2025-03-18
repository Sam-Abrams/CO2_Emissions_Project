# Global CO2 Emissions Clustering Analysis

## Project Overview
This repository contains an analysis of global carbon emissions patterns using clustering techniques to identify natural groupings of countries based on their emissions profiles. By analyzing emissions intensity, energy source mix, and historical contributions, this project reveals distinct country archetypes that can inform differentiated climate policy approaches.

## Key Features
- **Unsupervised Machine Learning**: Applied hierarchical clustering to identify natural country groupings
- **Dimensionality Reduction**: Used PCA to visualize high-dimensional emissions data
- **Multi-level Analysis**: Developed both 5-cluster and 8-cluster solutions for different levels of granularity
- **Interactive Visualization**: Created Tableau storyboard to explore emissions clusters

## Repository Structure
01 **Project Management**: Contains project planning documents, timelines, and requirements
02 **Data**: Houses raw datasets and processed data files
03 **Scripts**: Includes Python scripts and Jupyter notebooks for data processing and analysis
-- **01_data_preparation**.ipynb: Data cleaning and feature engineering
-- **02_clustering_analysis**.ipynb: Clustering implementation and visualization
04 **Analysis**: Contains analysis outputs, charts, and the cluster profiles report
-- cluster_profiles_report.md: Detailed analysis of cluster characteristics
-- emissions_clusters_for_tableau.csv: Final dataset with cluster assignments
05 **Sent to Client**: Final deliverables and presentation materials
-- Tableau workbooks and storyboards
-- Final presentation documents
README.md: Project overview and repository guide

## Methodology
The analysis uses a comprehensive dataset of global carbon emissions with metrics including:
- CO2 emissions per capita
- Energy source mix (coal, oil, gas proportions)
- Cumulative historical emissions
- Population and economic indicators

Countries were clustered based on these features, revealing distinct emissions profiles:
1. **Moderate Mixed-Source Emitters**: Balanced energy portfolio with medium emissions intensity
2. **Oil-Dependent Low-Impact Economies**: Oil-dominant with lower historical emissions
3. **Coal-Dependent Heavy Emitters**: Coal-reliant with high per-capita emissions
4. **Gas-Dominant High Per-Capita Emitters**: Gas-focused with the highest per-capita emissions
5. **Exceptional Emitter**: The United States, with a unique emissions profile unlike any other nation

The more detailed 8-cluster solution provides additional granularity for in-depth analysis.

## Key Findings
- The United States consistently appears as a unique outlier in both clustering solutions
- Countries naturally group based on both emissions intensity and dominant energy sources
- Historical emissions correlate with certain energy portfolio patterns
- High per-capita emitters fall into distinct categories based on their dominant fossil fuel

## Technologies Used
- **Python**: Data processing and clustering analysis
- **scikit-learn**: Machine learning implementation
- **pandas & numpy**: Data manipulation
- **matplotlib & seaborn**: Data visualization
- **Tableau**: Interactive storyboard creation

## Future Development
Future extensions to this project may include:
- Temporal analysis to track how countries move between clusters over time
- Forecasting models to predict future emissions trajectories by cluster
- Policy simulation to model intervention impacts on cluster transitions


## Contact
[Sam Abrams](sabrams15@gmail.com)
