# Password Strength Checker and Generator
This repository contains a Python project for checking the strength of passwords and generating random strong passwords. The program evaluates the password's strength based on various factors like the inclusion of lowercase, uppercase letters, numbers, whitespace, and special characters. It also provides feedback on how to improve the password.

## Features
Password Strength Checker: Analyzes the password and provides feedback based on strength.
Password Generator: Generates a random strong password that includes a mix of letters, digits, and special characters.
Interactive UI: A simple interactive user interface using ipywidgets that allows users to input passwords and generate new ones with a button click.
How it Works
Password Strength Checker:

It checks for the presence of:
Lowercase letters
Uppercase letters
Digits
Whitespace characters
Special characters
Based on the presence of these elements, the password is scored on a scale from 1 to 5 and categorized with remarks such as "Very weak password" to "Very strong password".
Password Generator:

Generates a random 12-character password with a mix of uppercase and lowercase letters, digits, and special characters.
Installation
To run this project, you need to have Python installed. You also need to install the necessary Python libraries:

bash
Copy code
pip install ipywidgets
How to Use
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/rahulsingh7111711/Pswd_Check.git
cd Pswd_Check
Run the Jupyter Notebook:
Open the notebook Pswd_Strength.ipynb in Jupyter Notebook or Jupyter Lab. You can launch Jupyter by running the following command in your terminal (if Jupyter is installed):

bash
Copy code
jupyter notebook Pswd_Strength.ipynb
Interact with the Application:
Check Password Strength: Enter a password in the text box and click the "Check Password Strength" button to see its strength and feedback.
Generate Strong Password: Click the "Generate Strong Password" button to create a random password and see its strength evaluation.
Example
When you input a password, the program will output something like:

yaml
Copy code
Password has:
2 lowercase letters
3 uppercase letters
2 digits
0 whitespaces
2 special characters
Password Score: 4/5
Remarks: Strong password, but could be improved.
For a randomly generated password, it will output:

yaml
Copy code
Generated Password: L5#qK9m^zR8
Password has:
4 lowercase letters
4 uppercase letters
2 digits
0 whitespaces
2 special characters
Password Score: 5/5
Remarks: Very strong password!
License
This project is licensed under the MIT License - see the LICENSE file for details.

