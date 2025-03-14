# CC-Validator

This program validates credit card numbers using the Luhn Algorithm, a simple checksum formula used by most major credit card companies. It helps detect accidental errors in card numbers by verifying their validity.

# How It Works
The program follows the Luhn Algorithm, which consists of the following steps:

### 1) Input a credit card number:

- The user is prompted to enter a credit card number.
- If the user enters "exit", the program will terminate.
- If the input contains non-numeric characters, the program prompts the user to enter a valid number.
### 2) Applying the Luhn Algorithm:

- Double every second digit from the right (starting from the second-to-last digit).
- If doubling results in a two-digit number, sum the individual digits (e.g., 8 × 2 = 16 → 1 + 6 = 7).

- Add all the processed numbers together.
- Add the sum of the remaining digits (those that weren’t doubled).
- If the total sum is a multiple of 10, the credit card number is valid; otherwise, it’s invalid.
### 3) Output the result:

- If the final sum is a multiple of 10, the program prints "Valid!"
- Otherwise, it prints "Invalid!"
- The process continues until the user chooses to exit.

# 🎯 Features
✅ Implements Luhn’s Algorithm for card validation.

✅ Supports continuous validation until the user chooses to exit.

✅ Error handling for invalid (non-numeric) inputs.

✅ Works with Visa, MasterCard, Amex, and other credit card formats.
