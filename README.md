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
Developed by:SRINIDHI SENTHIL
RegisterNumber: 22001408
'''
def max_marks(marks):
    m=max(marks)
    return m 
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: SRINIDHI SENTHIL 
RegisterNumber: 22001408
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: SRINIDHI SENTHIL
RegisterNumber: 22001408
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
           max1=i
    return max1

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://user-images.githubusercontent.com/121373170/213900192-fd6a5306-17fb-4358-8b4a-f48dc5d43929.png)

ii)	# To find the maximum marks using the list method max().
![image](https://user-images.githubusercontent.com/121373170/213900196-5170027e-8732-42a5-bea0-715ca6d7d41c.png)

iii) # To find the maximum marks without using builtin functions.
![image](https://user-images.githubusercontent.com/121373170/213900204-238840c3-d2cb-4292-886c-941b5d45377f.png)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
