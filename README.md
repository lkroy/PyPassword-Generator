# PyPassword Generator

## Overview
PyPassword Generator is a simple Python script designed to generate secure passwords based on user-defined criteria such as the number of letters, symbols, and numbers required in the password.

## How it Works
The script prompts the user to specify the number of letters, symbols, and numbers they want in their password. Based on these inputs, it generates a password in two levels: easy and hard.

### Easy Level
In the easy level, the order of characters (letters, symbols, and numbers) in the password is not randomized. This means that the letters will appear first, followed by the symbols, and then the numbers.

### Hard Level
In the hard level, the order of characters in the password is randomized. This enhances security by making it more difficult for potential attackers to predict the pattern of the password.

## Usage
1. Run the script.
2. Follow the prompts to specify the number of letters, symbols, and numbers for your password.
3. The script will generate both an easy and a hard level password.
4. Copy the desired password for your use.

## Files
- `password_generator.py`: The main Python script containing the password generation logic.
- `README.md` (this file): Provides an overview of the project, usage instructions, and other relevant information.

## Dependencies
This script requires Python 3 to run.

## Additional Notes
- Ensure that you remember or securely store the generated password, as it will not be saved by the script.
- Exercise caution when using generated passwords, especially in sensitive contexts. Always prioritize security best practices such as using unique passwords for different accounts and changing passwords periodically.

