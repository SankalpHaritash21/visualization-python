# Objective: Learn to load standard datasets and create common visualizations using several Python libraries (Matplotlib, Seaborn, Pandas plotting, Plotly).

Understand when to use which library and how to customize plots.

## Recap differences between the libs:

    1. Matplotlib: low-level, highly customizable.
    2. Seaborn: statistical visuals built on Matplotlib, nicer defaults.
    3. Pandas plotting: quick plots for DataFrames.
    4. Plotly: interactive, good for web/dashboards.

Homework: Create a multi-panel figure (subplot grid) combining at least 3 plots and export as PNG.

## Why visualize?

    1. Easier to understand trends, relationships, and distributions.
    2. Good for EDA (Exploratory Data Analysis) before applying ML.

## Common plots:

    1. Scatter plot → relationship between two numeric variables.
    2. Line chart → trends over time or sequence.
    3. Bar chart → compare categories.
    4. Histogram → distribution of a single numeric variable.
    5. Heatmap → correlations or pivoted tables

## Workflow:

1. Load dataset (sns.load_dataset("iris"))
2. Explore data (df.head(), df.info())
3. Choose right plot
4. Customize (labels, legends, title, grid, color)
5. Save if needed (plt.savefig("plot.png"))

## Task todo:

1. Scatter plot – Iris dataset:

   - Sepal length vs sepal width (different colors for species).
   - Do it in Matplotlib and Plotly.

2. Line chart – MPG dataset:

   - Show average mpg across model years.
   - Use Pandas plotting.

3. Bar chart – Tips dataset:

   - Show average total bill per day.
   - Use Seaborn barplot.

4. Histogram – Tips dataset:

   - Plot distribution of tip with KDE curve.
   - Use Seaborn histplot.

5. Heatmap – Iris dataset:
   - Plot correlation matrix.
   - Use Seaborn heatmap.
