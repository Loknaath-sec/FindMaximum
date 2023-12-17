# Exp-3a - Find the maximum of a list of numbers
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
#Program to mark the maximum of marks using the list method sort
#Developed by: P.LOKNAATH
#RegisterNumber: 23004546

def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
``` 
#Program to find the maximum marks using the list method max().
#Developed by: P.LOKNAATH
3RegisterNumber: 23004546

def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
#Program to the maximum marks without using builtin functions.
#Developed by: P.LOKNAATH
#RegisterNumber: 23004546

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![image](https://github.com/Loknaath-sec/FindMaximum/assets/145742558/b82397c4-c910-48fe-a9a5-f343f0d505b1)
![image](https://github.com/Loknaath-sec/FindMaximum/assets/145742558/6719fcc6-20cf-49e7-8d47-36a20373aa84)
![image](https://github.com/Loknaath-sec/FindMaximum/assets/145742558/2264bdbb-4aa9-46fa-b65c-35169ab3c449)


## Output:
![image](https://github.com/Loknaath-sec/FindMaximum/assets/145742558/e2f237ea-dcda-4709-9413-468257351af7)
![image](https://github.com/Loknaath-sec/FindMaximum/assets/145742558/671b8d4b-0f04-4792-849e-f08e07f97bdb)
![image](https://github.com/Loknaath-sec/FindMaximum/assets/145742558/318e8058-4cb0-48fe-b54d-d174aa449d90)

## Name: P. LOKNAATH
## REgister Number : 212223240080

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
