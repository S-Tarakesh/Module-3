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
string='google'
if string==string[::-1]:
    print(f"string {string} is a palindrome.")
else:
    print("It is not a palindrome")
```
## Output
<img width="917" height="771" alt="image" src="https://github.com/user-attachments/assets/000b9b50-abee-4650-8822-9948a4460891" />

## Result
The program was run and executed succesfully.
