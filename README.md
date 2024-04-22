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

Developed By: ASHWINA K N

Register Number: 212223230025

i)	# To find the maximum of marks using the list method sort.
```
def max_marks(arr):
    arr.sort()
    return arr[-1]
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(arr):
    r=max(arr)
    return r

```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(arr):
    max1=arr[0]
    for i in range(1,len(arr)):
        if max1<arr[i]:
            max1=arr[i]
    return max1

```



## Output:

![EXP-6](https://github.com/Ashwinakn/FindMaximum/assets/152128332/31881c48-2cb5-454e-9fde-329c57bb4112)

![EXP-6 2](https://github.com/Ashwinakn/FindMaximum/assets/152128332/322d1018-4afd-4570-97ac-f940d8370e89)

![EXP-6 3](https://github.com/Ashwinakn/FindMaximum/assets/152128332/5a140c65-aee2-45fb-a3eb-da160fc698b7)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
