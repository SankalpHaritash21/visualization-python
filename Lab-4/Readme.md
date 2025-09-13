# Use different data visualization techniques to filter the data.

1. Filtering Data in Pandas

   Filtering = selecting rows from a DataFrame that match certain conditions.

   - df[condition]

   ```
   # Equal to
   df[df['column'] == 'value']

   # Greater than
   df[df['column'] > 10]

   # Less than
   df[df['column'] < 5]

   # Not equal to
   df[df['column'] != 'value']

   ```

   2. Combining Conditions

   We can combine multiple conditions using & (AND) and | (OR).
   Always use ( ) brackets around each condition.

```
    # AND condition
    df[(df['col1'] > 10) & (df['col2'] == 'Yes')]

    # OR condition
    df[(df['col1'] < 5) | (df['col2'] == 'No')]

```

## Task Todo:

    1. Filter only Lunch data.
    2. Who tipped more Male or Female.
    3. Filter Sunday Dinner bills > 30 and  plot average tip by gender.
    4. Filter only female customers who gave a tip greater than 5.
    5. What's the use of Conditions (==, >, <, &, |)
    6. Filter bills greater than 40 and plot average tip by gender.
    7. Compare tips on weekends vs weekdays using bar plot.
