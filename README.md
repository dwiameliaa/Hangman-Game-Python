# Hangman Game

Hangman is a word-guessing game developed using Python. In this version, players are required to log in first by entering their username. After logging in, players will directly enter the game.

In the terminal, a visualization of the hangman will be displayed, gradually progressing each time the player guesses a letter incorrectly. Additionally, the following information will be shown during the game:

- **Topic**: The category of the word to guess, such as "Car" or others.
- **Score**: The points earned from guessing the current word.
- **Total Score**: The cumulative score from all correctly guessed words so far.
- **Chances**: The number of incorrect guesses remaining before the game ends.

Players must guess the word by selecting letters one at a time. There is one clue in the available letters: the letter displayed in uppercase represents the first letter of the word to guess. If the guess is correct, the letter will appear in its correct position in the word. Conversely, if the guess is incorrect, the number of chances will decrease, and the hangman visualization will progress closer to completion.

Each correctly guessed word will add to the player’s score. After completing one word, the player will proceed to the next word, with each word having a specific score value. However, if the player runs out of chances (maximum incorrect guesses until the hangman is fully drawn), the game will end, and a leaderboard will be displayed, showing the total score accumulated by the player.


# Prerequisites
Before you start, ensure you have the following installed on your system:

1. **Python 3.x**: You can download it from python.org.
2. **Git**: To clone the repository. Install it from git-scm.com.

# How to Run

Follow these steps to run the project:

1. Clone the repository:
```git clone https://github.com/dwiameliaa/Hangman-Game-Python.git```

2. Navigate to the project directory:
```cd Hangman-Game-Python```

3. Create a virtual environment (optional but recommended):
```python -m venv venv```

4. Activate the virtual environment:
  - **On Windows**:
```venv\Scripts\activate```

  - **On macOS/Linux**:
```source venv/bin/activate```

5. Install required dependencies:
Install dependencies by running:
```pip install -r requirements.txt```

6. Run the project:
```python hangman.py```

# Project Structure
- **hangman.py**: The main script to run the game.
- **leaderBoard.txt**: A text file that stores the leaderboard, including player scores and rankings.
- **bankSoal.txt**: A text file that contains a collection of words or phrases to be guessed by the players in the game.
