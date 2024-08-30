# Account Manager

This is a simple account management tool for accounts, designed to manage multiple Ubisoft accounts and allow you to automatically log into the Ubisoft Connect application with a selected account.

## How to Use

1. Run the application using Python.
2. Add your Ubisoft accounts using the "Add Account" button.
3. Select an account from the list and click "Login with Selected Account" to automatically log in.

## Requirements

- Python 3.x
- PyAutoGUI
- Tkinter (usually included with Python)

## Security Notice

Passwords are stored in plain text in a JSON file. This is not secure, and it's recommended to encrypt your passwords if you plan to use this application in a real-world scenario.

## Setup

1. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the application:
   ```bash
   python AccountManager.py
   ```

## Disclaimer

Automating logins might violate the terms of service of Ubisoft. Use this application at your own risk.
