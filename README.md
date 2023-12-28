# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
Developed by:Sanjai S
RegisterNumber:23003393
'''
def selection_sort(nums):
    n=len(arr)
    for i in range(n-1):
        index=i
        for j in range(i+1,n):
            if arr[j]<arr[index]:
                index=j
        arr[i],arr[index]=arr[index],arr[i]
    return arr


arr= eval(input())
print(selection_sort(arr))
```
ii)	#Insertion Sort
```
Developed by:Sanjai S
RegisterNumber:23003393
'''
def insertion_sort(arr):
    for i in range(1,len(arr)):
        a=arr[i]
        j=i-1
        
        while j>=0 and a<arr[j]:
            arr[j+1]=arr[j]
            j-=1
        arr[j+1]=a
    return arr
    
    
    
arr= eval(input())
print(insertion_sort(arr))
```
  

## Output:
![Screenshot 2023-12-28 162024](https://github.com/Sanjaikee/Sorting-Algorithm/assets/150231888/a9391275-de7c-4176-915a-60ee643f849a)
![Screenshot 2023-12-28 162042](https://github.com/Sanjaikee/Sorting-Algorithm/assets/150231888/d0c8d4cd-ba5d-4024-8370-7df57d42953a)




## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
