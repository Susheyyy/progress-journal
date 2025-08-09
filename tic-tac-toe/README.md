# TicTacToe 
<hr>

**Semester 2 Mini Project (Java, Swing GUI)**  
<br><br>
A classic Tic-Tac-Toe game built from scratch using Java and Swing. This project focuses on learning GUI development, event handling, and basic game logic in Java. It allows two players to take turns playing on the same computer, with automatic win/tie detection.

<b> <h3> ⚝ How It Works: </b></h3>

1. Game Window Setup:
    A JFrame window is created with a title panel (for game messages) and a 3x3 grid panel (for buttons). Each button represents a cell on the Tic-Tac-Toe board.

2. Turns & Gameplay:
    Randomly decides whether X or O starts. Players take turns clicking empty cells. The game updates the message panel to indicate whose turn it is.

3. Win/Tie Detection:
    After every move, the game checks all rows, columns, and diagonals for a win. Highlights the winning line in blue and disables further moves. If all cells are filled with no winner, the game declares a Tie.

4. Game End:
    Displays a winning message (“X WINS” / “O WINS”) or “It’s a Tie!”.  No further moves are allowed until the program restarts. <hr>

<b> <h3> ⚝ Tech Stack: </b></h3>

1. Programming Language: Java  
2. GUI Library: Swing (JFrame, JPanel, JLabel, JButton)
<hr>

<b> <h3> ⚝ Installation & Run: </b></h3>
- Clone or Download the repository 
- Compile and run

```bash
javac Application.java TicTacToe.java
java Application
