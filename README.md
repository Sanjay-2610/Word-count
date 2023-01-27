# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Getting the filename as input and creating a variable to store the number of words in the file
### Step 2: 
 Opening the file in read mode in r as f
### Step 3: 
 Getting the lines using the for loop
### Step 4:  
Creating a list in the for loop for storing the words in a libe
### Step 5: 
Adding the number of words in the list to the num variable
### Step 6: 
Printing the number of words in the file
## PROGRAM:
### Word count using a normal method
```py
#Program to count the occourances of a word in a file
#Developed By : Sanjay Ragavendar M K
#Register Number : 22009286
file=input()
num=0
with open(file,'r') as f:
    for line in f:
        words=line.split()
        num+=len(words)
print('Number of words:',num)
```

### OUTPUT:

![image](https://user-images.githubusercontent.com/91368803/215003869-a73d404f-97b8-4660-85b5-56ffa1137b71.png)


## RESULT:
Thus the program is written to find the word count from a text.
