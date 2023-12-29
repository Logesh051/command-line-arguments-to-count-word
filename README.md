# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Import the sys.
### Step 2: 
Open the file and assign it to data.
### Step 3: 
Read the file and assign it to data.
### Step 4:  
Split the data(data.split()).
### Step 5: 
Print the word count by len(word).
### Step 6: 
Close the file f1.
## PROGRAM:

```Python
#python program for command-line-arguments
#Devloped by : Logesh.N.A
#Reference no : 23012242

import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close()
```
### OUTPUT:
![Screenshot 2023-12-29 234604](https://github.com/Logesh051/command-line-arguments-to-count-word/assets/144979188/1f4f746e-d7f5-4948-bffc-f5542267bf6f)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
