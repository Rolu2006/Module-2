# EX-05-Iterative statements
## AIM:
To write a ython Program to print numbers  range from M to N (including M and N values)
## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Step 1: Read an integer from the user and store it in variable m.

Step 2: Read another integer from the user and store it in variable n.

Step 3: Start a for loop from i = m to i = n (inclusive).

Step 4: Print the current value of i in each iteration of the loop.

Step 5: Print a blank line after the loop finishes.


## PROGRAM:
```
m=int(input())
n=int(input())
for i in range (m,n+1):
    print(i)
print()
```
## OUTPUT:
![Screenshot 2025-05-22 220806](https://github.com/user-attachments/assets/48fe55c5-a4de-4ac5-afda-587d94f8ba9e)

## RESULT:
Thus the program to write a ython Program to print numbers  range from M to N (including M and N values) has been executed successfully.
 
# EX-06-Functions:
## AIM:
To write Python Program to check if a number is a Perfect number using the concept of functions.
## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Check if the input number n is less than 1; if yes, return False.

Initialize a variable sum to 0 to hold the sum of divisors.

Loop from 1 to n-1 and add i to sum if i divides n evenly.

After the loop, compare if sum equals n.

Return True if equal (perfect number), else return False.

## PROGRAM:
```
def per_num(n):
    sum=0
    for i in range(1,n):
        if n% i==0:
            sum+=i
    return sum==n
    if n<1:
        return false
n=int(input())
y=per_num(n)
if y:
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")
```
## OUTPUT:




![Screenshot 2025-05-22 221212](https://github.com/user-attachments/assets/eee6eb43-24d9-4078-8360-9b9e4f552987)





## RESULT:
Thus the program to write Python Program to check if a number is a Perfect number using the concept of functions has been executed successfully.
# EX-07-Built-In Funtions & Lambda Function
## AIM:
To Write a program in Python to calculate the value of the following expression by using lambda function.
The expression is -

(x + 10) + (y + 2) * z

## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Step 1: Define a lambda function result that takes x, y, and z, and computes (x + 10) + (y + 2) * z.

Step 2: Read an integer input and store it in x.

Step 3: Read another integer input and store it in y.

Step 4: Read a third integer input and store it in z.

Step 5: Call the result function with x, y, and z, then print the result.


## PROGRAM:
```
result=lambda x,y,z:(x + 10) + (y + 2) * z
x=int(input())
y=int(input())
z=int(input())
print(result(x,y,z))
```
## OUTPUT:
![Screenshot 2025-05-22 221656](https://github.com/user-attachments/assets/3e059dcf-2ef0-4b93-adcd-bf80dbbb9522)

## RESULT:
Thus the program Write a program in Python to calculate the value of the following expression by using lambda function.
The expression is -

(x + 10) + (y + 2) * z has been executed successfully.
# EX-08-Looping (Patterns)
# (a)
## AIM:
To Create a Python program to print the  simple number pattern using a for loop.



## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Step 1: Read an integer input and store it in rows.

Step 2: Loop through i from 1 to rows - 1.

Step 3: Convert i to a string and concatenate a space ' ' after it.

Step 4: Repeat this string i times to form the line.

Step 5: Print the resulting line.


## PROGRAM:
```
rows = int(input())

for i in range(1, rows ):
    print((str(i) + ' ') * i)
```
## OUTPUT:





![Screenshot 2025-05-22 222036](https://github.com/user-attachments/assets/a9df063c-1374-4ec1-9316-fb317abc4e1a)


## RESULT:
Thus the program to create a Python program to print the  simple number pattern using a for loop has been executed successfully.
# (b)
## AIM:
To write a Python Program to build pascal triangle using numbers .Get the number of rows as input .



## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Step 1: Create a list triangle with n rows, where each row i is initialized with i+1 elements set to 1.

Step 2: For each row i from 2 to n-1, calculate each element j (except the first and last) as the sum of the two elements above it.

Step 3: Update triangle[i][j] with the sum of triangle[i-1][j-1] + triangle[i-1][j].

Step 4: Iterate through each row in triangle.

Step 5: Print each row by joining its elements as space-separated strings.


## PROGRAM:
```
def pascal_triangle(n):
    triangle = [[1] * (i + 1) for i in range(n)]
    
    for i in range(2, n):
        for j in range(1, i):
            triangle[i][j] = triangle[i - 1][j - 1] + triangle[i - 1][j]
    
    for row in triangle:
        print(" ".join(map(str, row)))

rows = int(input())
pascal_triangle(rows)
```
## OUTPUT:





![Screenshot 2025-05-22 222338](https://github.com/user-attachments/assets/4f2efccd-ebd2-49bd-b83e-4cb0c37c6b48)





## RESULT:

Thus the program to write a Python Program to build pascal triangle using numbers has been executed successfully.










