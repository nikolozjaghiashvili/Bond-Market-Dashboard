# Bond Market Dashboard
#### Dashboard for SSA Bond Market Analysis

The purpose of this work is to create a dashboard that helps explore sovereign, supranational, and agency bond markets. The dashboard
helps visualize different characteristics of available bonds. Python plotly package is used to created visualizations for the dashboard. Jupyter
Notebook version of plotly Dash is used to add interactive features and link the visualizations in the dashboard. The dashboard consists of
three visualizations. First, the scatterplot of bond yields is plotted against bond maturities, with three different color encoding options.
Second, the time series of a specific bond yield. Third, the radar chart of characteristics of a specific bond yield. The dashboard allows
picking a specific bond (by clicking) in the scatterplot, which then adjusts the time-series and radar plot to display the characteristics for that
specific bond.

Two versions of this dashboard were deployed to Heroku Cloud

Version 1: https://bondmarket.herokuapp.com/
Version 2: https://newissuer.herokuapp.com/
