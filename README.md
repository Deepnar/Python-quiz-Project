# Python Quiz Game

A command-line quiz game using Python and MySQL.

## Features
- Multiple levels and participants
- Manager/admin mode for adding/removing questions
- Score tracking

## Setup

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Import the database:
   ```
   mysql -u root -p < quizapp.sql
   ```
3. Edit `quiz.py` to set your MySQL password if needed.

4. Run the game:
   ```
   python quiz.py
   ```

