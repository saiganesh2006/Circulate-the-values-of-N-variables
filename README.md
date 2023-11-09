# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the Program
### Step 2:
Get the inputs from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using concatication operation display the entire rotated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Depuru Bhargava Venkata Sai Ganesh
#RegisterNumber:23009248
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2023-11-09 110100](https://github.com/saiganesh2006/Circulate-the-values-of-N-variables/assets/145742342/a1aceda3-639f-48c7-95ab-0b64275219eb)

## Result:
Thus the python program for Circulating the values of n variables is executed successfully.
