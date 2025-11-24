
#README

Overview
A simple yet secure Python password generator that creates strong, randomized passwords with a balanced mix of lowercase letters, uppercase letters, numbers, and special characters.
Features

Generates passwords of user-specified length (minimum 6 characters)
Ensures password complexity with:

30% lowercase letters
30% uppercase letters
20% numbers
20% special characters


Input validation to ensure secure password length
Randomized character distribution for enhanced security

Requirements

Python 3.x
No external libraries required (uses built-in modules: string, random)

How to Run

Save the file as P2.py
Open terminal/command prompt
Navigate to the file directory
Run: python P2.py
Enter desired password length when prompted (minimum 6 characters)

Usage Example
How many characters do you want in your password? 12
Strong Password: aB3!xR9@mK2#

Project Description
This password generator is designed to help users create secure, random passwords that meet modern security standards. The program uses Python's built-in string and random modules to generate passwords with a balanced distribution of character types.
Key Components:

Character pools: Four separate lists containing lowercase letters, uppercase letters, digits, and punctuation marks
User input validation: Ensures passwords are at least 6 characters long and handles invalid inputs
Proportional distribution: Allocates character types based on percentage calculations (30-30-20-20 split)
Randomization: Shuffles both the character pools and final password for maximum unpredictability

Security Considerations:
The 6-character minimum enforces a baseline security requirement, though longer passwords (12+ characters) are recommended for sensitive accounts. The randomized distribution prevents predictable patterns that could be exploited.
