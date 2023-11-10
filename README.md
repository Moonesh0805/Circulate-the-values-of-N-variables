# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
program the code with def circulate.
### Step 2: 
Get the value from the user for the number of rotation
### Step 3:
print the circulating values
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
evaluate the a input.
### Step 6: 
enter integer (n) in input. 
## Program:
```
#Program to circulate N values.
#Developed by: Moonesh P
#RegisterNumber:23001144
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:

![OUTPUT](/image.png)

## Result:
Thus the Circulate the values of N variables are successfully executed.
