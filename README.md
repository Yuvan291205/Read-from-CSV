# Read-from-CSV

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
```
developed by : Yuvan M
Reg.no : 212223240188
import pandas as pd
df=pd.read_csv('cars (1).csv')
print(df.head(3))
print(df.tail(7))
print(df.axes[0],len(df.axes[0]))
print(df.axes[1],len(df.axes[1]))
print(df.loc[2:6,:])
```

## OUTPUT:
![Output](https://github.com/Yuvan291205/Read-from-CSV/assets/138849170/d84aed44-e7fb-417e-ab42-4df04a690ad3)


## RESULT:
Thus a python program is written to read the contents of a CSV file.
