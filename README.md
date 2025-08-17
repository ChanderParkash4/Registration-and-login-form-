# Registration-and-login-form-
This is a basic user authentication system in C++ using file handling.
It allows new users to register with a username and password, and later login using those credentials.

🔹 How it works:

Registration

User enters a username and password.

The credentials are stored inside a file called users.txt (in the format: username password).

Multiple users can register, as data is appended to the file.

Login

User enters their username and password.

The program reads through users.txt and checks if the entered credentials exist.

If found → Login successful ✅

If not found → Invalid username or password ❌

Menu-driven program

The user is presented with 3 options:

Register

Login

Exit

🔧 Key Concepts Used:

File Handling (ifstream, ofstream) → To store and retrieve login credentials.
Loops & Conditionals → To navigate menu and check authentication.
Strings → For username and password handling.
Basic Security → Passwords are stored as plain text (for learning purpose).
