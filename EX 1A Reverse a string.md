# EX 1A Reverse a String
## AIM:
Write a Python program to find the factorial of a given number using recursion.

## Algorithm

1.Define a function fact(n):

2.If n == 1, return 1 (base case).

3.Else, return n * fact(n-1) (recursive case).

4.Take input a from the user (as an integer).

5.Call the function fact(a) and print the result using formatted output.

## Program:
```
/*
Program to implement Reverse a String
Developed by: Harish R
Register Number: 212222110012
*/
```
```
def fact(n):
    if(n==1):
        return 1
    else:
        return n * fact(n-1)
a=int(input())
print("Factorial of number %d = %d"%(a,fact(a)))

```

## Output:
![Screenshot 2025-04-26 135118](https://github.com/user-attachments/assets/11a83a42-0880-484a-b2b0-022bfb094b6a)

## Result:
The program successfully calculates the factorial of a given number using recursion.
