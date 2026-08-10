🎯 Python Number Guesser

A simple command-line number guessing game built with Python. The program asks the user to choose an upper limit, generates a random number between 0 and that limit, and provides hints until the user guesses the correct number.

📌 Project Overview

This project is a beginner-friendly Python game focused on user input, random number generation, loops, conditionals, input validation, and tracking the number of guesses.

The game first asks the player to enter the top of the number range. It then generates a random number within that range and repeatedly asks the player to make a guess. After each incorrect guess, the program tells the player whether to choose a smaller or larger number.

✨ Features

User-defined upper limit

Random number generation

Input validation for the range

Input validation for guesses

Higher/lower guessing hints

Guess counter

Final attempt count

Command-line gameplay

🛠️ Technologies Used

Python 3

random module

Python Standard Library

Command-Line Interface

🎮 How the Game Works

Start
  ↓
Ask for upper range
  ↓
Validate input
  ├── Invalid → Exit
  └── Valid
       ↓
Generate random number
       ↓
Ask user for a guess
       ↓
Validate guess
       ↓
Compare guess with random number
   ┌───┴───────────────┐
   ↓                   ↓
Too high            Too low
   ↓                   ↓
"Guess smaller"     "Guess larger"
   └─────────┬─────────┘
             ↓
       Correct guess?
             ↓
            Yes
             ↓
    Display number of guesses
             ↓
            End

⚙️ Requirements

Python 3.9+ recommended

No external packages are required

🚀 How to Run

Clone the repository:

git clone https://github.com/YOUR_USERNAME/python-number-guesser.git
cd python-number-guesser

Run the program:

python src/number_guesser.py

On some systems:

python3 src/number_guesser.py

💻 Example

Type a number: 50
make a guess: 25
you got it wrong! enter a larger number
make a guess: 40
you got it wrong! enter a smaller number
make a guess: 35
you got it right
You got it in 3 guesses

📚 What I Learned

This project demonstrates foundational Python concepts including:

Importing and using modules

Random number generation

User input

Input validation with isdigit()

Type conversion

if / elif / else conditions

while loops

Counters

Program termination with quit()

🚀 Future Improvements

Add difficulty levels

Add a maximum number of attempts

Add a replay option

Track the best score

Add multiple difficulty ranges

Add a graphical user interface

Add automated tests

Refactor the game into reusable functions

Handle negative numbers and more flexible numeric input

Provide a score based on attempts


📄 License

This project is licensed under the MIT License.
