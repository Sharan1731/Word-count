# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:open the file in read mode and handle it in test mood

### Step 2: Read the text using read() function.
 
### Step 3: spilt the text using space separtor.we assume that words in a sentance are separted by a sapce character

### Step 4:  The length of the split list should equal the numbers of words in the test file.

### Step 5: You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6: end tha progarm

## PROGRAM:
```
  # Program to find the number of words in a text file
  # Developed by:SHARAN.G
  # Register number:212223230203
  num=0
  with open("marvel.txt","r") as f1:
    for i in f1:
      word=i.split()
      num+=len(word)
  print("The number of words are in the file is",num)
```
### OUTPUT:
![image](https://github.com/AkilaMohan/Word-count/assets/144980172/0c08642e-3425-4451-b151-7725a731240f)



## RESULT:
Thus the program is written to find the word count from a text.
