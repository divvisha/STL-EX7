# Ex.No: 7 SORTING

### DATE: 27/09/2024                                                                           
### REGISTER NUMBER : 212221040044
### AIM: 
To write a python program for sorting and inspect for failures. 

### Algorithm:
1. Start the program.
2. Get the number of elements from user
3. Get the elements to be sorted
4. Traverse the array and sort the elements one by one
5. Print the sorted array
6. Stop the program.
   
### Program:
~~~
n=int(input("Enter the number of elements:"))
arr=[]
try:
for i in range(n):
a=float(input("Enter the element:"))
arr.append(a)
for i in range(n):
for j in range(n):
if(arr[i]<arr[j):
temp = arr[i]
arr[i] = arr[j]
arr[j] = temp
print(“The array after sorting: ”)
for i in range(n):
print(arr[i],end=’ ’)
except ValueError:
print(“Enter a valid number”)
~~~

### Output:
![Screenshot 2024-11-18 233021](https://github.com/user-attachments/assets/6cda448b-4ec5-454d-8dbc-28c83cd8309d)

### Result:
Thus, a program to check sorting has been written and test cases have been written and verified successfully.
