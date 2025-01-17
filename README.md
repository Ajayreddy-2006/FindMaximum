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
```
i)# To find the maximum of marks using the list method sort.
 
Program to mark the maximum of marks using the list method sort
Developed by: T.Ajay
RegisterNumber: 23007325

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

```
ii)	# To find the maximum marks using the list method max().

Program to find the maximum marks using the list method max().
Developed by: T.Ajay
RegisterNumber: 23007325

def max_marks(marks):
    large=max(marks)
    return large
    
```



```
iii) # To find the maximum marks without using builtin functions.

Program to the maximum marks without using builtin functions.
Developed by:T.Ajay
RegisterNumber:23007325

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
```


## Sample Input and Output
![image](https://github.com/Ajayreddy-2006/FindMaximum/assets/145742508/f44b5fb2-f78d-40d8-853b-07645b4e6080)

## Output:
## To find the maximum of marks using the list method sort.
![image](https://github.com/Ajayreddy-2006/FindMaximum/assets/145742508/b8c127a2-5056-4d2f-b45d-d64d551a57bb)

## To find the maximum marks using the list method max().
![image](https://github.com/Ajayreddy-2006/FindMaximum/assets/145742508/ef19faa1-8543-47aa-8873-533992b82d15)

## To find the maximum marks without using builtin functions.
![image](https://github.com/Ajayreddy-2006/FindMaximum/assets/145742508/c829ba07-5e0f-417b-b050-f58ad2c3c7bb)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
