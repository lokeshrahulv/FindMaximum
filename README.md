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
Developed by: LOKESH RAHUL V V
RegisterNumber: 22004702

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Lokesh Rahul V V
RegisterNumber: 22004702

def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
``` 
Program to the maximum marks without using builtin functions.
Developed by: Lokesh Rahul V V
RegisterNumber: 22004702

def max_marks(list1):
    maximum=list1[0]
    for i in list1:
        if i>maximum:
            maximum=i
    return maximum    
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

![image](https://user-images.githubusercontent.com/118423842/213899984-74198740-9996-47c3-8cd2-1496ee633265.png)

![image](https://user-images.githubusercontent.com/118423842/213900013-f19b6f23-8fba-4799-9729-03980d4afcc9.png)

## Output:
![image](https://user-images.githubusercontent.com/118423842/213900022-f0109409-6413-468e-8ef3-6736979b303b.png)

![image](https://user-images.githubusercontent.com/118423842/213900029-662ab513-d430-4d66-918e-89aef53640f0.png)

![image](https://user-images.githubusercontent.com/118423842/213900033-5e983e50-d9a1-46ac-9fc6-31eb0218501c.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
