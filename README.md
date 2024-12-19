Hangman is a word-guessing game developed using Python. In this version, players are required to log in first by entering their username. After logging in, players will directly enter the game.

In the terminal, a visualization of the hangman will be displayed, gradually progressing each time the player guesses a letter incorrectly. Additionally, the following information will be shown during the game:

- **Topic**: The category of the word to guess, such as "Car" or others.
- **Score**: The points earned from guessing the current word.
- **Total Score**: The cumulative score from all correctly guessed words so far.
- **Chances**: The number of incorrect guesses remaining before the game ends.

Players must guess the word by selecting letters one at a time. There is one clue in the available letters: the letter displayed in uppercase represents the first letter of the word to guess. If the guess is correct, the letter will appear in its correct position in the word. Conversely, if the guess is incorrect, the number of chances will decrease, and the hangman visualization will progress closer to completion.

Each correctly guessed word will add to the player’s score. After completing one word, the player will proceed to the next word, with each word having a specific score value. However, if the player runs out of chances (maximum incorrect guesses until the hangman is fully drawn), the game will end, and a leaderboard will be displayed, showing the total score accumulated by the player.

