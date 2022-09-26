# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Assign the word count = 0.
### Step 2: 
Open the text file in read mode.
### Step 3: 
Read the contents using for() loop.
### Step 4:  
Split the words using built-in function split().
### Step 5: 
Increament the word count by using built-in function len().
### Step 6: 
Print the output.
## PROGRAM:
```python
'''
Program to get the word count from a text.
Developed by: R LAKSHANA
RegisterNumber: 22004909
'''
num_words=0
with open("unit 4.txt","r") as file1:
    for i in file1:
        word = i.split()
        num_words += len(word)
print('Number of Words = {}'.format(num_words))
```

## OUTPUT:

![text](/Text.png)

![output](/Output.png)

## RESULT:
Thus the program is written to find the word count from a text.
