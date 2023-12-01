# TH-task-3
# Rock-Paper-Scissors Game

This Python script implements a simple Rock-Paper-Scissors game where the user competes against the computer. The game consists of five rounds, and the winner is determined based on the number of rounds won by the user and the computer.

# How to Play

1. Run the script using a Python interpreter:
   ```bash
   python rock_paper_scissors.py
   ```

2. Enter your choice (Rock, Paper, or Scissors) when prompted.

3. The computer will randomly choose its move.

4. The winner of each round is determined based on the choices made:
   - Rock beats Scissors.
   - Scissors beats Paper.
   - Paper beats Rock.

5. The overall winner of the game is declared after five rounds.

6. You can choose to play the game again or exit.

# Code Breakdown

- **Game Functionality:**
  - The game is played in a loop for five rounds.
  - User input is received, and the computer randomly selects its move.
  - The winner of each round is determined, and scores are updated.

- **Scoring:**
  - Scores are maintained for both the user and the computer.
  - The overall winner is decided based on the total number of rounds won.

- **Play Again:**
  - After completing the game, the user has the option to play again.
  - The loop continues until the user decides not to play again.

# Potential Improvements

- **Input Validation:**
  - Add input validation to ensure that the user enters a valid choice (Rock, Paper, or Scissors).

- **Expand Choices:**
  - Consider expanding the game by introducing more choices or additional rules.

- **Enhanced User Interface:**
  - Create a graphical user interface (GUI) for a more interactive experience.

# Example Output

Welcome to Rock-Paper-Scissors Game!
Round: 1
Choose Rock, Paper, or Scissors: Rock
You choose: Rock
Computer choose: Scissors
Result: You win!
Your score: 1
Computer score: 0

... (Output for each round)

Round: 5
Choose Rock, Paper, or Scissors: Paper
You choose: Paper
Computer choose: Rock
Result: You win!
Your score: 3
Computer score: 1

Congratulation You win the game!
Play again? (yes/no): yes
... (Game repeats)
Play again? (yes/no): no
Thanks for playing the Rock-Paper-Scissors game!

# sample video

https://github.com/Srivarthaniselvam/TH-task-3/assets/151417502/b9842693-ed31-4775-91bf-fd96d9e2651f


# License

This project is licensed under the [MIT License](LICENSE).
