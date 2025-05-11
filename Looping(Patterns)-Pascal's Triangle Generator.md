# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. 2.	Read integer ‘a’ from user. 
3.	Outer loop 
      1.	Loop over i from 0 to a-1 (each row in Pascal's Triangle). 
4.	Inner Loop 
      1.	For each row i, print (a-i-1) spaces to align the numbers correctly. 
5.	Inner Loop(Binomial coefficients): 
      1.	For each row i, loop over j from 0 to i (this will print the elements of the row). 
      2.	For each j, calculate the Binomial coefficient using math package: i!//j!*(i−j)! 
      3.	Print the Binomial Coefficient without a newline (use end=" "). 
6.	Print new line
7.	End


---

## 🧪 Program
```
from math import factorial 
a=int(input())
for i in range(a):
    for j in range (a-i-1): 
        print(end=" ")
for j in range(i+1): 
        print(factorial(i)//(factorial(j)*factorial(i-j)),end=" ")
print() 
```

## Sample Output

![Screenshot 2025-05-11 164309](https://github.com/user-attachments/assets/a2546826-6834-43d3-8576-1822e91af19b)


## Result
Thus, the python program to print Pascal triangle is created successfully.
