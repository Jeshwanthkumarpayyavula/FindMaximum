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
Developed by: P.Jeshwanth Kumar
RegisterNumber: 23002519
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Developed by: P.Jeshwanth Kumar
RegisterNumber: 23002519
'''
def max_marks(marks):
   max_marks=max(marks)
   return max_marks





```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Developed by: P.Jeshwanth Kumar
RegisterNumber: 23002519
'''
def max_marks(list1):
    max_numbers=0
    for num in list1[1:]:
        if num>max_numbers:
            max_numbers=num
    return max_numbers        



```
## Sample Input and Output
''' 
![image](https://github.com/Jeshwanthkumarpayyavula/FindMaximum/assets/145742402/cfefdeaa-78fe-4a1a-bc77-144697ada2cd)
![image](https://github.com/Jeshwanthkumarpayyavula/FindMaximum/assets/145742402/b55e2fa1-ada5-48ef-8137-02053412c469)
![image](https://github.com/Jeshwanthkumarpayyavula/FindMaximum/assets/145742402/bbbdfc85-3161-4148-bc88-66a82a33de1f)




## Output:
![image](https://github.com/Jeshwanthkumarpayyavula/FindMaximum/assets/145742402/8349887d-eba0-43b3-9498-7e9bcfb3f72c)
![image](https://github.com/Jeshwanthkumarpayyavula/FindMaximum/assets/145742402/3d98d357-1fd8-4e35-ab18-3bff26576237)
![image](https://github.com/Jeshwanthkumarpayyavula/FindMaximum/assets/145742402/465fb66c-7c86-4ade-ac15-470ff8e3861d)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
