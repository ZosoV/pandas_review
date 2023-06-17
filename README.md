# Pandas Review

I plan to review the following topics that I supposed are the minimal for a 
job interview.

## Contents

| Topic                 | Link | Functions of Interest |
|-----------------------|------|-----------------------|
| Introduction to Pandas: Series, DataFrame, and Basics | <a href="001_intro_to_pandas.ipynb"> <img src="https://www.kindpng.com/picc/m/81-811458_jupyter-notebook-logo-hd-png-download.png" width="50" /> </a> | `pd.Series()`, `pd.DataFrame()`, `df.to_numpy()`, `df.info()`, `df.index`, `df.columns`, `df.shape`, `df.dtypes`, `df.astype()`     |
| Data Manipulation: Indexing, Slicing, and Filtering | <a href="002_indexing_slicing_filtering.ipynb"> <img src="https://www.kindpng.com/picc/m/81-811458_jupyter-notebook-logo-hd-png-download.png" width="50" /> </a>     | `df[<column_name>]`,`.loc[]`, `.iloc[]`, `.where()`    |
| Data Manipulation: Inserting and Deleting |      |      |
| Data Manipulation: Multi-index |      | `pd.MultiIndex.<function2create>()`, `df.index.levels`, `df.index.get_level_values(level)`, `.reindex()`, `.reset_index()`, `.set_index()`, `.align()`, indexing and slicing wiht MultiIndex, `df.loc(axis = 0)[]`, `.xs()`, `swaplevel()`, `reorder_levels()`, `rename()`, `rename_axis()`, `index.set_names()`, `sort_index()`, `index.is_monotic_increasing()`    |
| Data Manipulation: Sorting, Merging |      |      |
| Data Manipulation: Reshaping |      |      |
| Data Cleaning: Handling Missing Data |      |      |
| Aggregation and Grouping Operations |      |      |
| Time Series Analysis (Windowing Operations) |      |      |
| Data Manipulation: Arithmetic Operations (Optional) |      |      |
| Performance Optimization (Optional) |      |      |
| Visualization (Optional) |      |      |
