## Random-password-generator-python
This is a random password generator tool that creates strong, secure and customizable passwwords. It helps users in generating random passwords based on their chosen criteria such as length, symbols and uppercase/lowercase letters.

## Password Generator – Python Project

A secure and fully customizable Password Generator built using Python.

This project follows the academic and documentation standards of the Build Your Own Project guidelines and demonstrates practical implementation of user input handling, loops, functions, randomization, and validation logic.




## Table of Contents


Overview


Project Objectives


Features


Functional Requirements


Non-Functional Requirements


System Architecture


Workflow Diagram


Technologies Used


Installation


Usage


Project Structure


Sample Output


Testing


Challenges Faced


Future Enhancements


Author




## Overview

This Password Generator project creates strong, random passwords based on user-defined preferences such as:



Minimum password length


Inclusion of numbers


Inclusion of special characters



The script ensures all constraints are satisfied before returning a final password.
This project emphasizes clean code, modular functions, validation logic, and real-world utility.


## Project Objectives


To design and implement a functional password generation system.


To apply Python concepts such as loops, functions, and built-in modules.


To build a real-world utility tool following proper design & documentation guidelines.


To ensure the project meets both functional and non-functional requirements.




## Features


✔️ Customizable minimum password length


✔️ Option to include digits


✔️ Option to include special characters


✔️ Ensures all conditions are met before generating output


✔️ Simple and user-friendly CLI interface


✔️ Function to calculate password length


✔️ Modular and maintainable code




## Functional Requirements


Generate a password of user-defined minimum length.


Option to include:


Numbers


Special characters




Validate that generated password meets criteria.


Provide a function to return the length of the generated password.


Display the final password to the user.




## Non-Functional Requirements


Usability: Simple command-line interface.


Security: Produces strong, hard-to-guess passwords using Python’s secure character sets.


Efficiency: Fast generation using built-in modules.


Reliability: Consistent password generation meeting user criteria.


Maintainability: Clean, modular code with proper function usage.




## System Architecture
Modules


Input Module: Captures user choices.


Password Generator Module: Assembles character sets, generates password.


Validation Module: Ensures password meets requirements.


Output Module: Displays final password and length.




## Workflow Diagram (Text-Based)
Start
   ↓
User Inputs (length, numbers, special characters)
   ↓
Build character set based on choices
   ↓
Generate random characters
   ↓
Check if password meets criteria
   ↓ Yes               ↓ No
Return password    Continue loop
   ↓
Display Output
   ↓
End


🛠 Technologies Used


Python 3


Built-in modules:


random


string






## Installation
Clone the repository:
git clone https://github.com/yourusername/password-generator.git
cd password-generator



## Usage
Run the script:
python main.py

You will be asked:


Minimum password length


Whether you want numbers


Whether you want special characters




## Project Structure
Password-Generator/
│── main.py
│── README.md
│── Password_Generator_Project_Report.pdf



##  Sample Output
Input:
Enter the minimum length : 10
Do you want to have numbers(y/n)? y
Do you want to have special characters(y/n)? y

Output:
The generated password is: Af8@kP#19Z
password length : 10



##  Testing
The script was manually tested for:


Enforcing minimum length


Inclusion of numbers only


Inclusion of special characters only


Both numbers & special characters


Edge cases (length = 1, numbers disabled, etc.)




##  Challenges Faced


Ensuring password satisfies requirements within a single random-generation loop


Managing dynamic character sets based on user choices


Balancing simplicity with proper validation logic




## Future Enhancements


GUI version using Tkinter


Generate multiple passwords at once


Password strength meter


Save passwords to a file


Web version using Flask / Django



##  Author
Ananya Varshney

Feel free to fork, improve, and contribute!
