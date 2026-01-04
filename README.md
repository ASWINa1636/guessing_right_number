###🔍 Program Summary: Number Guessing Game with Hints
## ✅ Purpose:
This Python script is a simple number guessing game where:

The computer picks a random number between 1 and 100.

The player tries to guess it.

The program gives hints after each guess:

"Hot" if the guess is close (within ±10 of the number).

"Cold" if the guess is far (more than ±10 away).

"Right" if the guess is correct.

## 🧠 How it Works:
Random Number Generation:

A random number between 1 and 100 is generated using the random.randrange() function.

# Hint System:

Cold: If the guess is more than 10 away from the actual number.

Hot: If the guess is within 10 of the number but not exact.

Right: If the guess is exactly the correct number.

User Interaction Loop:

The program runs in a while True loop.

The user inputs a number repeatedly.

The game ends when the user guesses the number correctly.

## 🧪 Example Run:
text
Copy
Edit
Enter a number between 1 and 100: 23
Cold
Enter a number between 1 and 100: 45
Hot
Enter a number between 1 and 100: 50
You guessed it Right!
## 💡 Key Features:
Uses the random module.

Input loop with while True.

Hint-based feedback.

Simple and beginner-friendly logic.
