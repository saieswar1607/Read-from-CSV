# Read-from-CSV

## AIM:

To write a python program to read content from a csv file.

## ALGORITHM:

### Step 1:

Start python

### Step 2:

Import the required csv file.

### Step 3:

Import pandas

### Step 4:

Read the csv file by using df.read.

### Step 5:

Display the Columns.

### Step 6:

Display the Rows.

### Step 7:

End the program
## PROGRAM:
~~~
##Developed by: K. Sai Eswar    
##REGISTER NUMBER: 212221240020
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
~~~

## OUTPUT:
<img width="776" alt="Screenshot 2022-02-22 at 2 47 17 PM" src="https://user-images.githubusercontent.com/93427011/155100973-89415e03-5fcb-4b54-93ca-c38059edf772.png">
## RESULT:
Therefore the above python code is successfully executed to read the content from a csv file.
