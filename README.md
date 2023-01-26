# Read-from-CSV

## AIM:
to read from csv file

## ALGORITHM:
step1
Import pandas as pd.

Step 2:
Read the CSV file using read_csv method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns.

Step 5:
Print the output.

PROGRAM:
```
# Developed by: joel p
# Register Number: 22008934

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![e3f4902c-54e5-4c01-be23-d18fb755eb2a](https://user-images.githubusercontent.com/118626456/214861339-a1b888bd-1f71-40ef-80fe-57f154c9b663.jpg)


## RESULT:
hence the experiment was executed successfully
