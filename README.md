*Password Strength Checker
Overview:
This is a simple desktop application built using Python's Tkinter library. It allows users to check the strength of their password instantly. The app rates entered passwords as "Weak", "Medium", or "Strong" based on a few basic criteria.

Features:

User-friendly graphical interface

Secure password input (input hidden)

Checks for:

Minimum length (8 characters)

Presence of uppercase and lowercase letters

Presence of numbers

Presence of special characters

Real-time feedback on password strength

How to Use:

Run the provided Python script.

In the application window, enter the password you wish to check.

Click the "Check Strength" button.

The result will appear, showing your password's strength level.

Technical Requirements:

Python 3.x

tkinter (usually comes pre-installed with Python)

re (regular expression module, comes with Python)

How it Works:

The program analyzes the password’s length and character content.

It awards points for meeting criteria: length, uppercase, lowercase, digit, and special character.

The total score determines the rating:

Weak (≤2 points)

Medium (3-4 points)

Strong (5 points)
