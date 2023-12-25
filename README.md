# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0
### Step 2: 
open it with text file
### Step 3: 
Give range for i
### Step 4:  
Then next split the words
### Step 5: 
count the number of words
### Step 6: 
Giving print statement for getting output
## PROGRAM:
```
#Program to count the number of words in a text file'
#Developed by: MOHAMED RIDWAN A
#RegisterNumber: 23003133

count=0
with open ('file1.txt','r') as f:
    for line in f:
        word=line.split()
        count+=len(word)
    print(f'number of words in the file is : {count}')
```
### OUTPUT:
<img width="368" alt="image" src="https://github.com/MOHAMEDRIDWAN/Word-count/assets/146993368/ac462cd5-59e6-4010-9149-d1e35e9b92cc">



## RESULT:
Thus the program is written to find the word count from a text.
