# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the n variables from the user
### Step 2: 
Get the input
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the value it would be interchange
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Pavithra.S
#RegisterNumber:23012348
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
    
```

## Output:
![image](https://github.com/pavithraselvaraj30/Circulate-the-values-of-N-variables/assets/149366880/1e6b98a7-4b01-4a4b-97e0-a71d299af601)
## Result:
Thus the circulation of n variables successfully executed.
