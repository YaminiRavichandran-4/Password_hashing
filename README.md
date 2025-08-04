This is a simple Python script that demonstrates secure password hashing and verification using the bcrypt library.

📜 Features
Hash a user-provided password with a random salt

Securely verify passwords using bcrypt.checkpw

Demonstrates how to avoid storing plain text passwords

🚀 How to Run
Install dependencies
Make sure you have bcrypt installed:

bash
Copy
Edit
pip install bcrypt
Run the script

bash
Copy
Edit
python password_hasher.py
Follow the prompts

Enter a password → it will generate a hashed version

Re-enter the password → it checks if it matches the original

🧠 Code Overview
python
Copy
Edit
import bcrypt

