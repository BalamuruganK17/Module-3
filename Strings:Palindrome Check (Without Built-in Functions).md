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

## 🧾 Program:
```
def palindrome(a):
    x1=a[::-1]
    if a==x1:
       print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
    
    
string =input()
palindrome(string)
```
## Output:
<img width="964" height="155" alt="Screenshot 2026-04-21 132352" src="https://github.com/user-attachments/assets/9f7d21ba-d14b-46ef-b8c6-7df16eff0e10" />



## Result:
Thus the program to check whether a string is palindrome or not is executed successfully.



