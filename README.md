# Pandas Review

I plan to review the following topics that I supposed are the minimal for a 
job interview.

## Contents

| Topic                 | Link | Functions of Interest |
|-----------------------|------|-----------------------|
| Introduction to Pandas: Series, DataFrame, and Basics | <a href="001_intro_to_pandas.ipynb"> <img src="https://www.kindpng.com/picc/m/81-811458_jupyter-notebook-logo-hd-png-download.png" width="50" /> </a> | Data Structures: `pd.Series()`, `pd.DataFrame()` <br> Handy Functions: `df.to_numpy()`, `df.info()`, `df.index`, `df.columns`, `df.shape`, `df.dtypes`, `df.astype()`, `.rename()`, `.rename_axis()` <br> Iteration: `items()`, `iterrows()`, `itertuples()`    |
| Data Manipulation: Indexing, Slicing, and Filtering | <a href="002_indexing_slicing_filtering.ipynb"> <img src="https://www.kindpng.com/picc/m/81-811458_jupyter-notebook-logo-hd-png-download.png" width="50" /> </a>     | Indexing and Slicing: `df[<column_name>]`,`.loc[]`, `.iloc[]` <br> Filtering: conditional indexing (as numpy), `.where()`    |
| Data Manipulation: Inserting and Deleting |      |      |
| Data Manipulation: Multi-index |      | Creation: `.from_arrays()`, `.from_tuples()`, `.from_product()` <br> Properties: `index.levels`, `index.names`  <br> DataFrame Multi-index: `.reindex()`, `.reset_index()`, `.set_index()`, `.align()` <br> Indexing and Slicing: `.loc[<tuple of lists>]`, `.loc[<list of tuple>]`,`slice()`, `df.loc(axis = 0)[]`, `.xs()` <br> Multi-index functions: `swaplevel()`, `reorder_levels()`, `index.set_names()`, `sort_index()` |
| Data Manipulation: Sorting, Merging |      | Concatenation: `concat()` (multiple parameters) <br> Merging: `merge()`, `join()` (multiple parameters) <br> Comparing: `compare()`   |
| Grouping Operations: Aggregation, Transformation and Filtering | <a href="006_group_by.ipynb"> <img src="https://www.kindpng.com/picc/m/81-811458_jupyter-notebook-logo-hd-png-download.png" width="50" /> </a>     | Splitting: `groupby()` <br> Applying: `aggregate()`, `transform()`, `filter()`, `apply()` (can use built-in and UDF functions)  |
| Data Manipulation: Reshaping | <a href="007_reshaping.ipynb"> <img src="https://www.kindpng.com/picc/m/81-811458_jupyter-notebook-logo-hd-png-download.png" width="50" /> </a>     | `pivot()`, `pivot_table()`, `stack()`, `unstack()`, `melt()`  |
| Windowing Operations | <a href="008_windowing_operations.ipynb"> <img src="https://www.kindpng.com/picc/m/81-811458_jupyter-notebook-logo-hd-png-download.png" width="50" /> </a>       | `.rolling()`, `.expanding()`, `.ewm()` <br> Properties: `min_periods`, `center`, `closed`, `.apply()`, `corr()`, `cov()`   |
| Data Cleaning: Handling Missing Data (Optional) |      |      |
| Time Series Analysis (Optional) |      |      |
| Data Manipulation: Arithmetic Operations (Optional) |      |      |
| Performance Optimization (Optional) |      |      |
| Visualization (Optional) |      |      |


## References

I edit, organize, and add more examples to the content of this review is such a way that it is more understandable. However, it is important to mention that this review is based on three main sources:

1. The official [pandas user guide](https://pandas.pydata.org/docs/user_guide/index.html)
2. A real python review: [The pandas DataFrame: Make Working With Data Delightful](https://realpython.com/pandas-dataframe/#:~:text=The%20Pandas%20DataFrame%20is%20a,with%20in%20Excel%20or%20Calc)
3. A medium article: [Pandas Illustrated: The Definitive Visual Guide to Pandas](https://betterprogramming.pub/pandas-illustrated-the-definitive-visual-guide-to-pandas-c31fa921a43#76b7)