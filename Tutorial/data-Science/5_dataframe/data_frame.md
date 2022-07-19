# Python DataFrame

## Create a DataFrame with Pandas
- A data frame is a structured representation of data.
- Here is a data frame with 3 columns and 5 rows.
  ```python
  import pandas pd
  d = {'col1': [1,2,3,4,7], 'col2': [4,5,6,9,5], 'col3': [7,8,12,1,11]}
  df = pd.DataFrame(data=d)
  print(df)
  ```
- [All the code is explained here](data_frame.ipynb)
