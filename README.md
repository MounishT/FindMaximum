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
```
Program to mark the maximum of marks using the list method sort
Developed by: T MOUNISH
RegisterNumber: 23002806
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
Program to mark the maximum of marks using the list method sort
Developed by: T MOUNISH
RegisterNumber: 23002806
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by:T MOUNISH
RegisterNumber: 23002806
def max_marks(marks):
    large=max(marks)
    return large
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-25 084042](https://github.com/MounishT/FindMaximum/assets/138955798/23d1824b-62a8-4680-b688-98b4057336c0)
![Screenshot 2023-12-25 084042](https://github.com/MounishT/FindMaximum/assets/138955798/ccca1e62-4e81-421c-a314-39b93dd6450e)
![Screenshot 2023-12-25 084213](https://github.com/MounishT/FindMaximum/assets/138955798/58494bc8-e659-46f8-90e6-5f9e50107058)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
