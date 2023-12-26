# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it

### Step 2:
Open the text1.txt file in read mode

### Step 3:
Create a copy.txt file using write mode

### Step 4:
Copy the content of text1.txt file to copy.txt using write function:

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: RAHUL.V
RegisterNumber: 23006860

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![Screenshot 2023-12-26 143840](https://github.com/23006860/copy-file/assets/139841752/5cc55d16-8615-4508-a58e-9ab2f95dc59d)
![Screenshot 2023-12-26 143852](https://github.com/23006860/copy-file/assets/139841752/f26e98c7-c3e4-4333-8e26-568305a9198d)
![Screenshot 2023-12-26 143904](https://github.com/23006860/copy-file/assets/139841752/3da2baf9-453d-4d55-9980-594cab7e7418)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
