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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: yuva krishna k
RegisterNumber: 212222110056
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: yuva krishna k
RegisterNumber: 212222110056
'''
def max_marks(marks):
    return max(marks)



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: yuva krishna k
RegisterNumber: 212222110056
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max=i
    return  max


``` 

## Output:
![Screenshot (89)](https://github.com/Yuvakrishna0/FindMaximum/assets/117915037/1cd5c066-b749-4bc5-a721-1896ab4ca728)
<br>
![Screenshot (90)](https://github.com/Yuvakrishna0/FindMaximum/assets/117915037/1b2ae70b-68b1-4aff-8979-7c58c8e30284)
<br>
![Screenshot (91)](https://github.com/Yuvakrishna0/FindMaximum/assets/117915037/01555428-558d-4651-8c71-10133fa99fc1)
<br>
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
