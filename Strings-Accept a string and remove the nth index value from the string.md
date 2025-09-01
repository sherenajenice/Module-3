# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Start the program.
2. Define a function remove that takes a string as input.
3. Read an integer n (the index to remove) from the user.
4. Use string slicing to create a new string by:
5. Taking all characters before index n (string[:n])
6. Concatenating with all characters after index n (string[n+1:]).
7. Print the final string.
8. End the program

## 💻 Program
def remove(string):
   
    n=int(input())
   
    print(string[:n] + string[n+1:])
    

## Output
<img width="673" height="219" alt="image" src="https://github.com/user-attachments/assets/2db7d3c8-dfa4-4637-b85a-4139b3e1520f" />

## Result
Thus, To write a Python program that accepts a string and removes the character at a specified index is verified
