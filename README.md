# Read-from-CSV

## AIM:

To write a python program to read the datas from a CSV file.

## ALGORITHM:

### Step 1:

Download a CSV file

### Step 2:

Open a python platform

### Step 3:

Create a folder in python

### Step 4:

Copy the downloaded CSV file to the python folder


### Step 5:

Run the program

## PROGRAM:
```
#Program for reading content from CSV file
#Developed by: thanika sree b
#Register number: 22008978
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of colums:",len(df.axes[1]))
```

## OUTPUT:

![](/214927007-d037f152-ba09-4233-adf5-1b26bcd5024c.png)

## RESULT:

Thus the program is successfully executed.
