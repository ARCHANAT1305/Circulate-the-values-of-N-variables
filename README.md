# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Accept an integer value 'n' from the user using input() and eval()
### Step 2: 
Accept an another integer value 'm' from the user using input() and convert it to an integer int()
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the  result along with the circulated values

## Program:
```# Program to circulate N values.
# Developed by: ARCHANA.T
# RegisterNumber:23014066
def circulate():
    n = eval(input())
    m =int(input())
    n = n[m:]+n[:m]
    print("After circulating the values are:",n)
``````
## Output:

![Alt text](<Screenshot 2023-10-27 081911.png>)``



## Result:
Thus circulating the n variables was sucesssfully executed
