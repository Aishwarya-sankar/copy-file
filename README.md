# copy-file

## AIM:

To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 


## Step 1:

First we need to open the required file form which we need to copy the text. Again using the with keyword to open the empty file.


## Step 2:
Using keyword "with" to open the requied file.


## Step 3:
Again using the with keyword to open the empty fil


## Step 4:

The empty file is open by using 'W' which is used to write only.


## Step 5:

The four function is used to take each line from the main fi

## Step 6:
The four function is used to take each line from the main file.

## PROGRAM:
```python
#Developed by: Aishwarya S
#Reference no: 22008635
with open('file.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```

### OUTPUT:

![](./copy1.png)


![](./copy2.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.