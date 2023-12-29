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

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
