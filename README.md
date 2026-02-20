🔐 Random Password Generator (Python)

A simple Python script that generates a strong, random password using letters, digits, and special characters.

This project demonstrates the use of Python’s built-in libraries such as random and string to create secure passwords.

📌 Features

Generates a 16-character password

Includes:

Uppercase letters (A–Z)

Lowercase letters (a–z)

Numbers (0–9)

Special characters (!, @, #, etc.)

Simple and lightweight script

Easy to customize password length

🛠️ Technologies Used

Python 3.x

random module

string module

📂 Project Structure
password-generator/
│
├── password_generator.py
└── README.md
▶️ How It Works

string.ascii_letters → Contains uppercase and lowercase letters

string.digits → Contains numbers 0–9

string.punctuation → Contains special characters

All characters are combined into one string.

random.sample() selects random unique characters.

"".join() combines them into a single password string.

🚀 How to Run

Ensure Python 3 is installed.

Save the code as password_generator.py

Open terminal or command prompt.

Navigate to the project folder.

Run:

python password_generator.py

A random 16-character password will be displayed.

🔎 Sample Output
aB#9xP!2mL@7qR$1

(Output will be different each time.)

⚙️ Customization

To change password length:

length = 20

To remove special characters:

total = string.ascii_letters + string.digits
⚠️ Important Note

random.sample() does not repeat characters in the password.

For cryptographic-level security, consider using:

import secrets

The secrets module is recommended for generating secure passwords in real-world applications.

🎯 Future Improvements

Add user input for password length

Add option to include/exclude special characters

Create a GUI version using Tkinter

Build a web-based password generator

📄 License

This project is open-source and free to use for educational purposes.
