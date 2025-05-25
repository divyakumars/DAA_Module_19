# EX 1D Linear search
## DATE: 01/03/25
## AIM:
To write a python program for a search function with parameter list name and the value to be searched.

## Algorithm
1. Start

2. Read an integer x (number of elements).

3. Read x elements into list List.

4. Read the element n to search.

5. For each element in List:

6. If the current element equals n, return its index.

7. If loop ends without a match, return -1.

8. If returned index ≠ -1, print "Found", else print "Not Found".

9. End

## Program:

Program to implement a search function with parameter list name and the value to be searched.

Developed by: DIVYA K

Register Number: 212222230035

```
def search(List1,n):
    for i in range(len(List1)):
        if (List1[i]==n):
            return i
    return -1
List = [] 
x=int(input())
for i in range(x):
    List.append(input())
n =input()
value = search(List, n)
if value!=-1:
	print("Found")
else:
	print("Not Found")
```

## Output:

![image](https://github.com/user-attachments/assets/019556e3-eb2f-475f-9bda-a3b0f81bbd0b)


## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
