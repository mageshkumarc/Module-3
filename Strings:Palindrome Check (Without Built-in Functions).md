# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
n=input()
pal=n[::-1]
if n==pal:
    print("The given number",n,"is a Palindrome")
else:
    print("The given number",n,"is not a palindrome") 
```

## Output
![image](https://github.com/user-attachments/assets/8587897a-749a-4c76-954e-b0fc0938cf84)

## Result
Thus,the program is executed successfully
