Name: Tabassum Mallikar 

Company: Encryptix 

ID: EXM260994

Domain: Python Programming

Duration: Oct to Nov 2024

**Overview of the Project**

**Project: Password Generator**

**Objective**

The objective of this program is to generate a secure random password based on user-defined length. It ensures the password contains at least one lowercase letter, one uppercase letter, one digit, and one special character for improved security. The program prompts the user for the desired password length, validates the input, and displays the generated password if the input is valid.

**Key Activities**

Input Validation: Prompts the user for the desired password length and checks if it’s a valid integer. 

Password Length Check: Ensures the password length is at least 4 characters for adequate security.

Character Set Definition: Defines the character sets used in the password (lowercase, uppercase, digits, and special characters).

Password Construction:
Randomly selects one character from each category to meet security requirements.
Fills the remaining characters from the combined character set.

Randomization: Shuffles the characters in the password to ensure randomness in order.

**Technologies Used**

Python: The programming language used for implementing the password generation logic.

Standard Libraries:
random: Used for generating random characters to ensure password variability.

string: Provides easy access to character sets like letters, digits, and punctuation for password creation.

**Key Insights**

Password Security: Ensures a minimum length of 4 characters for adequate security.

Character Variety: Guarantees inclusion of lowercase, uppercase, digits, and special characters in the password.

Randomization: Utilizes random.choices and random.shuffle to create a randomized password.

User Input Handling: Prompts the user for desired password length and includes error handling for invalid inputs.
