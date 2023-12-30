# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.
### Step 2: 
Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.

## PROGRAM:
```
## DEVELOPED BY: Sharan G
## REFERENCE NUMBER: 23002031
num_words =0
file1 = open("text.txt", "r")
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
## Text File:
```
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
```
### OUTPUT:

![image](https://github.com/Sharan1731/Word-count/assets/144980172/1c5c1020-1263-48b3-bac9-fc700f064137)
![image](https://github.com/Sharan1731/Word-count/assets/144980172/fb3b1256-7216-41a7-9607-28818287e939)


## RESULT:
Thus the program is written to find the word count from a text.
