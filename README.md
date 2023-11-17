# Ex5c-copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
Open the file f2 in append mode.
### Step 3: 
Copy the contents using write() with the for loop.

## PROGRAM:
```
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![image](https://github.com/Kishorekumar22060/copy-file/assets/141472136/f103a7fa-12bb-4248-869f-b41b01bcd4c0)

![image](https://github.com/Kishorekumar22060/copy-file/assets/141472136/9255b39b-5532-41bb-ae65-8ce2130a9061)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
