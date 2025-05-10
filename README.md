# Password Strength Checker

This is a C++ program that checks how strong a password is based on calculated password entropy.

## What It Does

- You type in a password.
- The program checks what type of characters are used (letters, numbers, symbols).
- It calculates how strong the password is by first calculating the total number of possible passwords.
- It takes into consideration that there are: 26 alphabets, 10 numerical digits and 32 special characters.
- After finding the total number of possible passwords it takes its log base 2 value which gives us the password entropy.
- If the password entropy is below 30, it informs the user that the password is not strong enough.

## How to Run It

1. Execute the CSCI262_Task1.exe file
2. Entire a password of your choice
3. The program calculates the entered passwords entropy and informs the user if the password is strong enough or not
   
