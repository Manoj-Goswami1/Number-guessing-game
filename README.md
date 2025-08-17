🎯 Number Guessing Game

A simple Python console game where the player has 7 chances to guess the secret number between a given range.

📌 How It Works

The program asks you to enter a lower bound and an upper bound.

It randomly selects a number within that range.

You have 7 attempts to guess the number.

After each guess, the program will give you hints:

"Too high!" → The number is lower.

"Too low!" → The number is higher.

If you guess correctly, you win!

If you use all 7 chances without guessing, the program reveals the number.

▶️ How to Run

Make sure you have Python 3 installed.

Save the script as number_guessing_game.py.

Open a terminal or command prompt in the script’s folder.

Run the game with:

python number_guessing_game.py

📖 Example Gameplay
Hi! Welcome to the Number Guessing Game.
You have 7 chances to guess the number. Let's start!

Enter the Lower Bound: 1
Enter the Upper Bound: 50

You have 7 chances to guess the number from 1 and 50. Let's start!
Enter your guess: 25
Too low! Try a higher number.
Enter your guess: 40
Too high! Try a lower number.
Enter your guess: 33
Correct! The number is 33. You guessed it in 3 attempts.

💡 Features

User-defined number range.

7 attempts limit.

Hints for each incorrect guess.

Victory or defeat message at the end.

🚀 Future Improvements

Add difficulty levels (Easy/Medium/Hard).

Track score across multiple rounds.

Allow replay without restarting the program.
