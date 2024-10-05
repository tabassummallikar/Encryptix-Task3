Name: Tabassum Mallikar

Company: Encryptix

ID: EXM260994

Domain: Python Programming

Duration: Oct to Nov 2024

**Overview of the Project**

**Project: Password Generator**

**Objective**
The objective of this project is to create a user-friendly password generator application using Python's Tkinter library. The application allows users to specify the desired length of the password and select various complexity options, including the inclusion of uppercase letters, lowercase letters, digits, and special symbols.

**Key Activities**
Import Libraries: Import necessary libraries (tkinter, messagebox, random, and string).

Define Function: Create the generate_password() function to handle password generation based on user inputs.

Get User Input: Retrieve password length and complexity options from the GUI.

Validate Options: Check if at least one character type is selected; show an error message if none are.

Generate Password: Create a random password by selecting characters based on user preferences.

Update GUI: Display the generated password in the GUI.

Setup GUI: Create the main window, labels, entry fields, checkboxes for options, and a button to trigger password generation.

Run Event Loop: Start the GUI event loop with root.mainloop() to keep the application running.

**Technologies Used**
Python: The programming language used for development.

Tkinter: A built-in Python library for creating graphical user interfaces (GUIs).

Random: A module in Python for generating random numbers and selections.

String: A module in Python providing access to string constants (like ASCII characters).

**Key Insights**
User Customization: The application allows users to specify the desired length of the password and select various complexity options (uppercase letters, lowercase letters, digits, and symbols) through checkboxes. This enables users to generate passwords tailored to their security needs.

Random Password Generation: The password is generated by randomly selecting characters from a combined string of the chosen character types. The use of random.choice ensures that the password is generated securely and with varying character distributions based on user preferences.

Error Handling: The program includes error handling to ensure that at least one character type is selected before generating a password. If no options are selected, it displays an error message, enhancing user experience and preventing invalid password generation.



![image alt](https://github.com/tabassummallikar/Encryptix-Task3/blob/752b95b9ddb78e73e17f72eff068bf6d1626f898/Screenshot%202024-10-05%20221454.png)
