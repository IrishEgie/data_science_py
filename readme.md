# Learning Points & Summary - Day 73

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


# Learning Points & Summary - Day 74

In this lesson we looked at how to:

- Use HTML Markdown in Notebooks, such as section headings `#` and how to embed images with the `<img>` tag.
- Combine the `groupby()` and `count()` functions to aggregate data.
- Use the `.value_counts()` function.
- Slice DataFrames using the square bracket notation (e.g., `df[:-2]` or `df[:10]`).
- Use the `.agg()` function to run an operation on a particular column.
- Rename columns of DataFrames with `rename()`.
- Create a line chart with two separate axes to visualize data that have different scales.
- Create a scatter plot in Matplotlib.
- Work with tables in a relational database by using primary and foreign keys.
- Use `.merge()` to combine DataFrames along a particular column.
- Create a bar chart with Matplotlib.

# Learning Points & Summary - Day 75

In this lesson we looked at how to:

- Use `.describe()` to quickly see some descriptive statistics at a glance.
- Use `.resample()` to make time-series data comparable to another by changing the periodicity.
- Work with `matplotlib.dates` Locators to better style a timeline (e.g., an axis on a chart).
- Find the number of NaN values with `.isna().values.sum()`.
- Change the resolution of a chart using the figure's DPI.
- Create dashed `'--'` and dotted `'-. '` lines using linestyles.
- Use different kinds of markers (e.g., `'o'` or `'^'`) on charts.
- Fine-tune the styling of Matplotlib charts by using limits, labels, linewidth, and colors (both in the form of named colors and HEX codes).
- Use `.grid()` to help visually identify seasonality in a time series.


# Learning Points & Summary - Day 76

In this lesson we looked at how to:

- Create arrays manually with `np.array()`
- Generate arrays using `.arange()`, `.random()`, and `.linspace()`
- Analyze the shape and dimensions of a `ndarray`
- Slice and subset a `ndarray` based on its indices
- Perform linear algebra operations with scalars and matrix multiplication
- Use NumPy's broadcasting to make `ndarray` shapes compatible
- Manipulate images in the form of `ndarrays`

# Learning Points & Summary - Day 77

Today was a pretty packed lesson where we introduced a lot of new concepts. In this lesson we looked at how to:

- Use nested loops to remove unwanted characters from multiple columns.
- Filter Pandas DataFrames based on multiple conditions using both `.loc[]` and `.query()`.
- Create bubble charts using the Seaborn Library.
- Style Seaborn charts using the pre-built styles and by modifying Matplotlib parameters.
- Use floor division (i.e., integer division) to convert years to decades.
- Use Seaborn to superimpose linear regressions over our data.
- Make a judgement if our regression is good or bad based on how well the model fits our data and the r-squared metric.
- Run regressions with scikit-learn and calculate the coefficients.

