# Pandas Review

I plan to review the following topics that I supposed are the minimal for a 
job interview.

## Contents

| Topic                 | Link | Functions of Interest |
|-----------------------|------|-----------------------|
| Introduction to Pandas: Series, DataFrame, and Basics | <a href="001_intro_to_pandas.ipynb"> <img src="https://www.kindpng.com/picc/m/81-811458_jupyter-notebook-logo-hd-png-download.png" width="50" /> </a> | Data Structures: `pd.Series()`, `pd.DataFrame()` <br> Handy Functions: `df.to_numpy()`, `df.info()`, `df.index`, `df.columns`, `df.shape`, `df.dtypes`, `df.astype()`, `.rename()`<br> Iteration: `items()`, `iterrows()`, `itertuples()`    |
| Data Manipulation: Indexing, Slicing, and Filtering | <a href="002_indexing_slicing_filtering.ipynb"> <img src="https://www.kindpng.com/picc/m/81-811458_jupyter-notebook-logo-hd-png-download.png" width="50" /> </a>     | Indexing and Slicing: `df[<column_name>]`,`.loc[]`, `.iloc[]` <br> Filtering: conditional indexing (as numpy), `.where()`    |
| Data Manipulation: Inserting and Deleting |      |      |
| Data Manipulation: Multi-index |      | Creation: `pd.MultiIndex.from_arrays()`, `pd.MultiIndex.from_tuples()`, `pd.MultiIndex.from_product()` <br> DataFrame Multi-index: `df.index.levels`, `df.index.get_level_values(level)`, `.reindex()`, `.reset_index()`, `.set_index()`, `.align()` <br> Indexing and Slicing with MultiIndex: `slice()`, difference between tuples and list, `df.loc(axis = 0)[]`, `.xs()`, `swaplevel()`, `reorder_levels()`, `rename()`, `rename_axis()`, `index.set_names()`, `sort_index()`, `index.is_monotic_increasing()`    |
| Data Manipulation: Sorting, Merging |      | Concatenation: `concat()` (multiple parameters) <br> Merging: `merge()`, `join()` (multiple parameters) <br> Comparing: `compare()`   |
| Data Manipulation: Reshaping |      | `pivot()`, `stack()`, `unstack()`, `melt()`, `pivot_table()`     |
| Data Cleaning: Handling Missing Data |      |      |
| Aggregation and Grouping Operations |      |      |
| Time Series Analysis (Windowing Operations) |      |      |
| Data Manipulation: Arithmetic Operations (Optional) |      |      |
| Performance Optimization (Optional) |      |      |
| Visualization (Optional) |      |      |
