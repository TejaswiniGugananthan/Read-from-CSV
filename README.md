# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output.
## PROGRAM:
```python
#To write a python program for reading content from a CSV file.
#eveloped by: Tejaswini.G
#Register Number: 22004187

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
<img width="303" alt="image" src="https://user-images.githubusercontent.com/121222763/214770236-68c60141-16c8-4c41-9121-4610dcb584b2.png">


## RESULT:
Thus a python program is written to read the contents of a CSV file.
