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
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
    
```

## Output:
![Screenshot 2024-04-08 160020](https://github.com/pavithraselvaraj30/Circulate-the-values-of-N-variables/assets/149366880/cb27d3bc-a1f9-4180-898a-a172976d3813)

## Result:
Thus the circulation of n variables successfully executed.
