# Importing and Exploring Data in Pandas (CSV, Excel, and SQL Formats)

# Objective

- To learn how to import data from different formats into Python using Pandas and perform basic exploration using .head(), .info(), and .describe().

## Working with CSV

```
import pandas as pd

df_csv = pd.read_csv("ipl_2023.csv")
print(df_csv.head())
print(df_csv.info())
print(df_csv.describe())

```

#### what do .head(), .info(), .describe() do?

1. .head():

   - Get a quick look at what the data looks like.
   - See the column names and first few values.

2. .info():

   - See total number of rows and columns.
   - Identify data types (int64, float64, object, etc.).
   - Check for missing (null) values.

3. .describe():
   - Know mean, median, std deviation, min, max, quartiles.
   - Detect outliers or strange distributions.
   - Understand value ranges of numeric fields.

```
Note:
What is an Outlier?

An outlier is a value that is very different (too high or too low) from other values in your data.
```

```
count: 5 players are listed.

mean: On average, players played 13.8 matches.

std: Very low (0.44), so all players played nearly the same number of matches.

min: At least 1 player played 13 matches.

max: The most anyone played is 14 matches.

50% (median): Most played 14.
```
