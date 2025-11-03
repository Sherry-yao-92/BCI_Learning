pandas -> for data analysis
import pandas as pd
import numpy as np

Data structure
DataFrame
2 dimension (Table)
pd.DataFrame({'Yes': [50, 21], 'No': [131, 2]}, index=['A','B'])
Yes No
A 50 21
B 131 2

        Yes/No -> Column
        A/B -> Row (index)

    Series
        A sequence of data values (List)
        pd.Series([30, 35, 40], index=['A', 'B', 'C'], name='Product')
        A 30
        B 35
        C 40
        Name: Product, dtype: int64

Read data
Comma-Separated Values: CSV file
Read CSV file into a DataFrame
data= pd.read_csv("path",index_col=0)
data.shape -> (rows, columns)
data.head -> Grabs the first five rows

Turn the DataFrame into CSV -> data.to_csv("File_name.csv")
