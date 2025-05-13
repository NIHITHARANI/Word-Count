# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Import numpy as np

Step 2:
Enter the input values

Step 3:
Write python program for getting the word count from the contents 

of a file using command line arguments

Step 4:
Run the program

Step 5:
Input the values

Step 6:
End the program
## PROGRAM:
```
#Program to find the number of words in a text file
#DEVELOPED BY : NIHITHA RANI B
#REGISTER NUMBER: 23012494

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:

![image](https://github.com/user-attachments/assets/da01945f-c44d-4064-b450-73c5098c7174)

## RESULT:
Thus the program is written to find the word count from a text.
