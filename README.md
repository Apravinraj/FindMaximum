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
Developed by: your name:Dinesh karthick.K.J
RegisterNumber: 22005847
'''
def max_marks(marks):
        marks.sort()
        return marks[-1]





```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Dinesh karthick.K.J
RegisterNumber: 22005847
'''
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:Dinesh karthick.K.J
RegisterNumber: 22005847
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i >max1:
            max1 = i
    return max1
```
## Output:
![Screenshot (45)](https://github.com/Apravinraj/FindMaximum/assets/118707879/01716f19-d526-4ea1-9975-5b6706b364a9)

![Screenshot (46)](https://github.com/Apravinraj/FindMaximum/assets/118707879/6e571fb9-a151-4c4c-bccf-6a20e456c7fb)


![Screenshot (47)](https://github.com/Apravinraj/FindMaximum/assets/118707879/3d9e9c3c-3cc4-4f61-8be7-1c4dee78c9c7)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
