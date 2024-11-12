# Password Strength Checker and Generator
This repository contains a Python project for checking the strength of passwords and generating random strong passwords. The program evaluates the password's strength based on various factors like the inclusion of lowercase, uppercase letters, numbers, whitespace, and special characters. It also provides feedback on how to improve the password.

## Features
  Password Strength Checker: Analyzes the password and provides feedback based on strength.
  Password Generator: Generates a random strong password that includes a mix of letters, digits, and special characters.
  Interactive UI: A simple interactive user interface using ipywidgets that allows users to input passwords and generate new ones with a button click.

## How it Works
### 1. Password Strength Checker:

  It checks for the presence of:
     Lowercase letters
     Uppercase letters
     Digits
     Whitespace characters
     Special characters
   Based on the presence of these elements, the password is scored on a scale from 1 to 5 and categorized with remarks such as "Very weak password" to "Very strong password".

### 2. Password Generator:

  Generates a random 12-character password with a mix of uppercase and lowercase letters, digits, and special characters.
