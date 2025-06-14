# pca-eigenvectors-visualization
Overview
This notebook demonstrates how to visualize Principal Component Analysis (PCA) transformed data in 2D using Plotly for an interactive and intuitive representation.

Key Steps:
Data Preparation:

The dataset is reduced to two principal components (PC1 and PC2).

The target variable is converted to string format to ensure correct color mapping in the scatter plot.

Plot Creation:

plotly.express.scatter is used to generate the scatter plot.

Each class (target) is represented with a distinct color using px.colors.qualitative.G10 for better clarity.

Marker Customization:

Marker size is set to 12.

Each marker is outlined with a border of width 2 and colored DarkSlateGrey for sharpness.

Plot Customization:

Title is added as "2D Transformed Data" to clearly communicate the content of the visualization.

Interactivity:

The final plot is rendered with fig.show(), which is fully interactive and supports zooming, hovering, and panning
