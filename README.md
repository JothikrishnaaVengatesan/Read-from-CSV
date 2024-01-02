# Read-from-CSV

## AIM:
To write a program to read the csv file and print head,tail and the number of rows and columns.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation

## ALGORITHM:
### Step 1:
Start the program.
### Step 2:
Import pandas.
### Step 3:
Read the file using built in function.
### Step 4:
Print head , tail and the number of rows and columns.
### Step 5:
End the program.

## PROGRAM:
### Program to read contents from a csv file 
### Developed by: JOTHIKRISHNAA V
### Register Number:212223100017
~~~python
import pandas as pd
df=pd.read_csv('nba (1).csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
~~~
## OUTPUT:
![read csv](<Screenshot 2024-01-02 113228.png>)
## RESULT:
Thus the program to read a csv file  is written and verified using python programming.