# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.


### Step 2: 
Using keyword "with" to open the requied file.
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The four function is used to take each line from the main file.
### Step 6: 
The four function is used to take each line from the main file.
## PROGRAM:
```
'''
Program for copying the contents from one file to another file.
Developed by: hanumanth
#RegisterNumber:22005234
'''
with open("git.txt","r") as f1:
    with open("MyFile.txt","a") as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![214319760-57de48b6-0ebd-41e3-bd33-f82029bc54db](https://user-images.githubusercontent.com/121033192/214795885-660778ed-5d45-474e-a4e4-c3c9823f390c.jpg)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
