# Swapping-two-values
## AIM:
To write a python program for swapping of two values
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the two values from the user
### Step 2: 
Assign the value of second variable to a temporary variable 
### Step 3: 
Assign the value of the first variable to the second variable.
### Step 4:  
Assign the value in temporary variable to the first variable
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## PROGRAM:
```
#Program to swap two values.
#Developed by:SRIKAAVYAA T 
#RegisterNumber:23013589
def swap(a,b):
    c=a
    a=b
    b=c
    return a,b
a=float(input())
b=float(input())
a,b=swap(a,b)
print("Swapped values are:",a,b)
```
 ## output:
 ![output](/output.png)
 

## RESULT:
Thus the swapping of two values are successfully executed



