# Study various data visualization libraries of Python (Matplotlib, Seaborn, Plotly)

## Remember

Think of visualization as the lens through which raw data becomes meaningful knowledge. Without it, even the best AI models remain a "black box.

## Explain why visualization is important in Data Science & AI.

1.  Makes Complex Data Understandable.
2.  Reveals Hidden Patterns
3.  Supports Better Decision-Making
4.  Essential in Model Development

        In AI/ML, visualization is used for:

        - Data exploration – checking distributions, class imbalance, missing values.
        - Model evaluation – plotting loss curves, ROC curves, precision-recall plots.
        - Model explainability – SHAP plots, decision trees, attention maps in deep learning

5.  Bridges the Gap Between Data & Action

# There sre some library for Data visualization

Popular Python Libraries for Visualization

1.  Matplotlib

        Foundation library for plots in Python.
        Supports line, bar, scatter, pie, histogram, etc.

        Example:
        import matplotlib.pyplot as plt
        plt.plot([1,2,3],[4,5,6])
        plt.show()

2.  Seaborn

        Built on Matplotlib, but easier & more stylish.
        Great for statistical plots (heatmap, boxplot, violin plot).

        Example:
        import seaborn as sns
        sns.histplot([1,2,2,3,3,3,4,4,5])

3.  Plotly

        Interactive & web-based plots (zoom, hover).
        Good for 3D, maps, dashboards.

        Example:
        import plotly.express as px
        px.scatter(x=[1,2,3], y=[4,5,6])

4.  Bokeh

- Interactive, web-ready visualizations.
- Often used for dashboards.

5. Altair

- Declarative & concise plotting library.
- Works smoothly with Pandas DataFrames.

Successfully studied Matplotlib, Seaborn, and Plotly libraries and implemented various types of data visualizations in Python.”

for evaluation:

1. Difference between Matplotlib and Seaborn?
2. Why use Plotly?
3. What does hue do in Seaborn?
4. How do you export/save a plot?
5. What’s the difference between a histogram and a KDE plot?
