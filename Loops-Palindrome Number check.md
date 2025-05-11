## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
temp=num
rev=0
while temp>0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10
if rev==num:
    print(f"The given number {a} is a Palindrome")
else:
    print(f"The given number {a} is not a palindrome")
```
## Output

![Screenshot 2025-05-11 164850](https://github.com/user-attachments/assets/f2d57c00-3376-4898-9f0f-4b78d6ecb6d0)


## Result
Thus,the python program that checks whether a given number is a **palindrome** using loops is created successfully.
