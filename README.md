![image](https://github.com/user-attachments/assets/b51617cb-3688-4f08-b566-c9b4e5ddb2f5)# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
 Write some lines in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output
## PROGRAM:
```python
#Program for copying the contents from one file to another file.
#Developed by HEMACHANDIRAN J 
#Reg num : 212224040113
with open("file1.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)

```
### OUTPUT:
program execution:

![image](https://github.com/user-attachments/assets/f8ae365b-8b74-4f60-bdd3-e95378f2b091)

copied file:

![image-1](https://github.com/user-attachments/assets/c676b54a-4f18-466f-83ef-b6a41db5c596)


text file:
![image-2](https://github.com/user-attachments/assets/bf2584e6-bbc5-4bbf-b979-70bd584091da)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
