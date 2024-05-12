# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.`

### Step 2: 
Create a file pointer and open the file which is passed in command line.

### Step 3: 
Initialize word count as zero.

### Step 4:  
For each line in file, split it into words and find number of the words in every line.

### Step 5: 
Sum the number of words in each line.

### Step 6: 
Display the total words in the file.

## PROGRAM:

#program for getting the word count from the contents of a file using command line arguments.

#Developed By: SRIVATSAN G

#Register Number: 212223230216

```
import sys
count=0
with open(sys.argv[1],'r') as f1:
     for i in fp:
        words=i.split()
        count+=len(words)
print("word count  in file is",count)
```
### OUTPUT:
![WhatsApp Image 2024-05-12 at 22 10 10](https://github.com/vatsan143/Command--line-arguments-to-count-word/assets/147368204/aa21642f-eec7-4a6e-af03-900b3f75604e)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
