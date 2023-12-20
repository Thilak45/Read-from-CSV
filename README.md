# Read-from-CSV

## AIM:

## ALGORITHM:
### step 1: Import pandas as pd.

### Step 2: Read the CSV file using read_csv method.

### Step 3: Use head and tail method to get the required contents from the file.

### Step 4: Use len() method to get the number of rows and columns.

### Step 5: Display the result

## PROGRAM:
```
'''
Developed by:vellachi tilak
Register No: 23009564
'''
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![WhatsApp Image 2023-12-20 at 23 32 21_2727bbe6](https://github.com/Thilak45/Read-from-CSV/assets/138849161/6c470799-249f-45b2-9e7c-af27e710612c)

### RESULT
thus python program for reading content from CSV file is successful
