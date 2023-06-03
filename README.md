# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: your name:Pravin raj.A
RegisterNumber: 212222240079
'''
def max_marks(marks):
        marks.sort()
        return marks[-1]

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Pravin raj.A
RegisterNumber: 212222240079
'''
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:Pravin raj.A
RegisterNumber: 212222240079
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i >max1:
            max1 = i
    return max1
```
## Output:
To find the maximum of marks using the list method sort.
![Screenshot 2023-06-03 192139](https://github.com/Apravinraj/FindMaximum/assets/118707879/19adee6c-e65b-4140-bb6f-b84714786b77)
To find the maximum marks using the list method max().
![Screenshot 2023-06-03 192206](https://github.com/Apravinraj/FindMaximum/assets/118707879/c810d3e5-87f3-431d-b085-2b16e7ca211f)
To find the maximum marks without using builtin functions.
![Screenshot 2023-06-03 191108](https://github.com/Apravinraj/FindMaximum/assets/118707879/b9943d28-afaa-4c1a-9c9f-baec3e4cb6a3)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
