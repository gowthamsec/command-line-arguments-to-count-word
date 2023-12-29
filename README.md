# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
~~~
#Program for getting the word count from the contents of a file using command line arg
#Developed by: GOWTHAM N
#Register Number : 23013437
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
~~~

### OUTPUT:
![OUTPUT](https://github.com/gowthamsec/command-line-arguments-to-count-word/assets/147933945/72c88225-a425-4a30-a1d7-222e302d1515)
![OUTPUT](https://github.com/gowthamsec/command-line-arguments-to-count-word/assets/147933945/9c526ab7-3e73-4cf2-8a50-e5090cec8ea2)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
