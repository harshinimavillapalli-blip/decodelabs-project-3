# decodelabs-project-3
This Python program is a secure password generator that creates random passwords of a user-specified length and evaluates their strength using entropy. It utilizes Python's built-in string, secrets, and math modules to generate cryptographically secure passwords and estimate their security level.

# Password Generator Application

A simple command-line based Password Generator built using Python. This project allows users to generate secure random passwords of a specified length and evaluates their strength using entropy calculations.

# Features

- Generate random passwords of any desired length
- Uses letters, numbers, and special characters
- Calculates password entropy
- Displays password security level
- Validates minimum password length
- Beginner-friendly implementation

# Technologies Used

- Python
- string module
- secrets module
- math module

# How It Works

The program prompts the user to enter the desired password length.

Users can:

- Enter a password length of 8 or more characters
- Generate a secure random password
- View the password's entropy value
- Check the password's security level

The password is generated using Python's `secrets` module, which is designed for cryptographically secure random number generation.

# How to Run

1. Install Python on your system.
2. Save the code in a file named `password_generator.py`
3. Open Terminal or Command Prompt.
4. Run the program using:

```bash
python password_generator.py
```

# Sample Output

```text
Enter password length: 12

Generated Password: #a7K!mP9@xL2
Entropy: 78.66 bits
Security Level: Moderate
```

# Learning Concepts

This project helps beginners understand:

- Functions in Python
- User input handling
- Exception handling (`try-except`)
- String manipulation
- Random password generation
- Cryptographic security concepts
- Entropy calculation using logarithms
- Conditional statements (`if-else`)

# Future Improvements

- Ensure at least one uppercase letter, lowercase letter, digit, and special character
- Allow users to customize character types
- Generate multiple passwords at once
- Copy generated passwords to clipboard
- Save passwords securely in an encrypted file
- Add a graphical user interface (GUI)

# Author
Mavillapalli Harshini
