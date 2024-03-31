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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=max(marks)
    return large
```
iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num
```
## Output:
![Screenshot 2024-03-31 150902](https://github.com/JAGADEESHJ97/FindMaximum/assets/152129419/7e1e1d73-b251-4281-83ee-414f93414141)
![Screenshot 2024-03-31 150913](https://github.com/JAGADEESHJ97/FindMaximum/assets/152129419/1a043296-a757-4de8-a51f-586dbef114ac)
![Screenshot 2024-03-31 150926](https://github.com/JAGADEESHJ97/FindMaximum/assets/152129419/600416c7-f014-42bc-8633-5bf6ebff493e)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
