# Email Parser

Welcome to the **Email Parser** project! This is a simple Python script that extracts the username and domain from a provided email address.

This project was built to practice:
- String manipulation in Python.
- Using the `input()` function for user interaction.
- Extracting substrings using indexing and slicing.

## Features

- Accepts an email address input in the format `username@domain.xyz`.
- Splits the email into the username and domain.
- Prints the extracted username and domain.

## How it works:

1. The program prompts the user to enter an email address.
2. It identifies the position of the `@` symbol using `index()` method.
3. It then extracts the username (the part before `@`) and the domain (the part after `@`) using string slicing.
4. The username and domain are displayed to the user.

### Sample Output
<img src="https://github.com/Coy0000/Email-slicer/blob/main/Capture1.PNG" height="80%" width="80%" alt="Start"/>
<br />
<br />

## Future Improvements

- Add validation to check if the email is in a valid format before processing.
- Handle cases where the `@` symbol is missing or there are multiple `@` symbols.
- Improve user experience by providing error messages for invalid inputs.

---


