This Java program implements a simple number guessing game where players try to guess a random number generated within a specified range. The game consists of multiple rounds, and in each round, players have a limited number of attempts to guess the correct number.

How to Play
Setup
The game generates a random number within a specified range (default: 1 to 100). Players have a limited number of attempts to guess the correct number (default: 10 attempts per round). The game consists of a total of 3 rounds.

Playing a Round
In each round, players are prompted to guess the number within the given range. After entering a guess, they will receive feedback indicating whether the actual number is greater or smaller than their guess. The goal is to guess the number within the allotted attempts for each round.

Scoring
Players earn points based on the number of attempts remaining after correctly guessing the number. The score for each round is calculated as:
Score = MAX_ATTEMPTS - attempts_taken

Total Score
The total score is the sum of scores from all rounds played.

Game Over
After completing the specified number of rounds, the game ends, and the player's total score is displayed.

Customize the Game
You can customize the game by adjusting the following constants in the Task2 class:

MIN_RANGE: Minimum value for random number generation.
MAX_RANGE: Maximum value for random number generation.
MAX_ATTEMPTS: Maximum attempts allowed to guess the number in each round.
MAX_ROUNDS: Total number of rounds in the game.
Running the Program
Compile the Java file (Task2.java).
Run the compiled Java program.
