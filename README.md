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
Developed by: NATARAJ KUMARAN S
RegisterNumber: 23003973
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: NATARAJ KUMARAN S
RegisterNumber: 23003973
'''
def max_marks(marks):
    a=max(marks)
    return a
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: NATARAJ KUMARAN S
RegisterNumber: 23003973
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
    
```
### Output:
### To find the maximum of marks using the list method sort.
![image](https://github.com/nataraj26/FindMaximum/assets/147514615/5e7617cd-99cd-4fd8-9ccb-74d18afc85e7)
### To find the maximum marks using the list method max().
![image](https://github.com/nataraj26/FindMaximum/assets/147514615/6fc36eac-182b-423c-a2e7-747334ac32cd)
### To find the maximum marks without using builtin functions.
![image](https://github.com/nataraj26/FindMaximum/assets/147514615/7d327217-dcee-4133-b3ca-2c02d6a44949)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
