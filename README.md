# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function named circulate with no parameters
### Step 2: 
Assign the value of eval(input()) to a variable named l
### Step 3: 
Assign the value of int(input()) to a variable named n
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print a message that says “After circulating the values are:” followed by the value of l
## Program:
```
#Program to circulate N values.
#Developed by: Gnanendran N
#RegisterNumber:23006661
def circulate():
    l=eval(input(""))
    n=int(input(""))
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![output](/circulate.png)

## Result:
Thus the circulating n variables using function concept is successfully executed