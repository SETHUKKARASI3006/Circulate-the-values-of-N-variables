# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create circulate() function
### Step 2: 
Get the list from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Store the rotated list value in a new list name
### Step 6: 
return the new list
## Program:
```
#Program to circulate N values.
#Developed by: Sethukkarasi C
#RegisterNumber:23012881
def circulate():
   p=[]
   p.extend(s[i:])
   p.extend(s[:i])
   return p
s=eval(input())
i=int(input())
print("After circulating the values are:",circulate())
```
## Output:
![output](/circulateoutput.png)
## Result:
