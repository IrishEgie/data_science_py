# Learning Points & Summary

## Today's Learning Points

- Use `.head()`, `.tail()`, `.shape`, and `.columns` to explore your DataFrame. These methods help you find the number of rows and columns, as well as the column names.

- Look for NaN (not a number) values using `.findna()`. Consider using `.dropna()` to clean up your DataFrame.

- Access entire columns of a DataFrame with square bracket notation:
  - Single column: `df['column name']`
  - Multiple columns: `df[['column name 1', 'column name 2', 'column name 3']]`

- Access individual cells in a DataFrame by:
  - Chaining square brackets: `df['column name'][index]`
  - Using `.loc[]`: `df['column name'].loc[index]`

- Find the largest and smallest values, as well as their positions, using:
  - Largest value: `.max()`
  - Smallest value: `.min()`
  - Position of largest: `.idxmax()`
  - Position of smallest: `.idxmin()`

- Sort the DataFrame with `.sort_values()` and add new columns using `.insert()`.

- Create an Excel-style Pivot Table by grouping entries that belong to a particular category with the `.groupby()` method.
