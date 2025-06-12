Python Quiz Game
A command-line quiz game built using Python and MySQL, supporting multiple participants, difficulty levels, and an admin interface for managing questions.

Features
Multiple quiz levels with increasing difficulty

Support for multiple participants

Admin/Manager mode to add, edit, or delete questions

Score tracking and result display

Getting Started
Prerequisites
Python 3.7 or higher
Download and install from python.org

MySQL Server
Download and install the MySQL Community Server from mysql.com

Install Python Dependencies
Use the following command:

bash
Copy
Edit
pip install mysql-connector-python
Database Setup
Import the SQL file into your MySQL server:

bash
Copy
Edit
mysql -u root -p < quizapp.sql
Make sure your MySQL user, password, and database name in the Python code match your local setup.

(Optional) Update Credentials

If your MySQL username or password is different, update the connection logic inside your Python file (likely in a function like connect_to_database()).

Running the Quiz Game
Once everything is set up, run the following command from your project directory:

bash
Copy
Edit
python quiz.py
(Replace quiz.py with the actual name of your Python file if it's different.)

Project Structure
bash
Copy
Edit
quiz.py           # Main game logic
quizapp.sql       # MySQL schema and sample data
README.md         # This file
Future Improvements (Optional)
Add a graphical interface (Tkinter or PyQt)

Account system for multiple managers

Ability to create difffernt set of questions based on type


