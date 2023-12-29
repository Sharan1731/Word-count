# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:Open the file in read mode and handle it in test mood.

Step 2:Read the text using read() function.

Step 3: Split the text using space separator.We assume that words in a sentance are separted by a space character.

Step 4:You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

Step 5:The length of the split list should equal the numbers of words in the test 

Step 6:End the program.
PROGRAM:
           Split the text using space separator.We assume that words in a sentance are separted by a space character.
    You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

## PROGRAM:
```
  # Program to find the number of words in a text file
  # Developed by:Ashwath M
  # Register number:212223230023
  num=0
  with open("marvel.txt","r") as f1:
    for i in f1:
      word=i.split()
      num+=len(word)
  print("The number of words are in the file is",num)
```

### OUTPUT:
![image](https://github.com/AkilaMohan/Word-count/assets/144980172/64a2ccaa-c7eb-47f1-8390-bf900b0fd2b0)




## RESULT:
Thus the program is written to find the word count from a text.
