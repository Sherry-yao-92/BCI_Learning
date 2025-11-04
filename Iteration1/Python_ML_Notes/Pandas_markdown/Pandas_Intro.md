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

Assess property of a DataFrame -> data.property or data['property']
Drill down to a single specific value -> data['property'][0]

Indexing
Index-based selection
Select data based on its numerical position
Select the first row of data in a DataFrame -> data.iloc[0]
Get a column with iloc -> data.iloc[:,0]
Negative numbers -> Start counting forwards from the end of the values
0:10 -> 0,1,2...,9

    Label-based selection
        Based on data index
        0:10 -> 0,1,2,...,10

Manipulate the index -> set_index()
e.g. set_index to the title field -> data.set_index("title")

Conditional selection
data.property == 'A' -> Produced a Series of True/False booleans
data.loc[data.property == 'A']-> Select the relevant data
& -> and, | -> or

    Built-in conditional selectors
        Select data whose value "is in" a list of values
        -> data.loc[data.property.isin(['A', 'B'])]

        Highlight values which are (or are not) empty (NaN)
        -> data.loc[data.property2.isnull] or data.loc[data.property2.notnull]

Assigning data
data['property'] = 'property2'
data['index_baxkwards'] = range(len(reviews), 0, -1)
