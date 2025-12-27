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

s = "google"
rev = s[::-1]
if s == rev:
    print(f'"{s}" is a palindrome')
else:
    print(f'"{s}" is not a palindrome')


## Output
<img width="405" height="150" alt="image" src="https://github.com/user-attachments/assets/8c4c0109-ceec-46a7-86d7-40622ef66030" />

## Result
thus the code excuted successfully
