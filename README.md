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

#Developed by: yuvabhrathi.b
#RegisterNumber:22002787 
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
#Developed by: yuvabharathi.b
#RegisterNumber: 22002787
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
#Developed by: yuvabharathi
#RegisterNumber: 22002787
def max_marks(list1):
    max1 = list1[0]
    for i in list1:
        if i>max1:
           max1 =i
    return max1 


```

## Output:
# 1 To find the maximum of marks using the list method sort.
![output](/q1.png)

# 2 To find the maximum marks using the list method max().
![output](/q2.png)

# 3 To find the maximum marks without using builtin functions.
![output](/q3.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.


