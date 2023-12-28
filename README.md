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
Developed by:RAMYA P
RegisterNumber:23006111 
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
Developed by:RAMYA P
RegisterNumber:23006111
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
![image](https://github.com/23006111/Sorting-Algorithm/assets/145981696/154404a9-bbe8-4212-9e34-86b6525bee7b)
![image](https://github.com/23006111/Sorting-Algorithm/assets/145981696/c7469143-7df7-4c69-9d11-b37fd953af8b)




## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
