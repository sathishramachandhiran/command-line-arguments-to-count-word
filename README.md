# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Import the sys module.

Step 2: Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

Step 3: Read the file using read() method.

Step 4: Use split() method to split the file content into words.

Step 5: Use len() to find the total words.

Step 6: Run the program to determine the number of words in the file created.
## PROGRAM:
```
#program is developed: SATHISH R
# REF.NO: 22009045
import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count += len(word)
print("program is developed: SATHISH.R")
print("word count in file = ",count)
```
### OUTPUT:
![prg](https://user-images.githubusercontent.com/120574768/214601216-61192857-9f4d-411c-af29-23cd4f874167.png)

![output](https://user-images.githubusercontent.com/120574768/214601243-0015f956-1c16-4910-b1c7-800099007038.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
