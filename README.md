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
def max_marks(marks):
    marks.sort()        # sort the list in ascending order
    return marks[-1]    # last element is the maximum


```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):
    maximum = marks[0]   # assume first element is max
    
    for i in marks:
        if i > maximum:
            maximum = i
    
    return maximum

```



## Output:

<img width="1208" height="418" alt="image" src="https://github.com/user-attachments/assets/4d591874-60c0-438e-a1f3-4916d99fd3f8" />
<img width="1211" height="363" alt="image" src="https://github.com/user-attachments/assets/764cbe96-2a7f-4ed6-9633-78962ffc922f" />
<img width="1206" height="330" alt="image" src="https://github.com/user-attachments/assets/71423c90-55ac-4dc4-93c2-0925efdc3db1" />


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
