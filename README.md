# onehot-encoder
This repository contains the code for one-hot encoding variables for data preprocessing for machine learning.

**Usage**

```python
from onehot_encoder import onehot_encoding # onehot encoding module

data = df.copy() # make a copy of the original dataframe (df)

column_to_dummy = ['column_A', 'column_B', 'column_C', ...,'column_Z'] # columns to one-hot encode

data = onehot_encoding(column_to_dummy, data) # perform operation

data.head()
```
