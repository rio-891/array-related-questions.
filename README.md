1) ## python program to find sum of array and printing the count of array using len() keyword.
## simple program
arr=[12,32,543,56,7,1]
n=len(arr)            ##count of array using len keyword.
print("The length of array is:", n)
sum=0
for i in arr:
    sum = sum + i
print("Sum of array is",sum)


2) ## Python Program to find largest element in an array using max keyword.


arr=[12,32,543,56,7,1]
n=len(arr)
print("The length of array is:", n)
sum=0
max=arr[0]
for i in range(n):
    if arr[i] > max:
        max=arr[i]
        
print("Largest number in array is:",max)  ## will print largest number in array.

3)
##Your goal in this kata is to implement a difference function, which subtracts one list from another and returns the result.

It should remove all values from list a, which are present in list b.


 r=[]
    for i  in a:
        if i  not in b:
            r.append(i)
    return r
