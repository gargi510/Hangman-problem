
# Hangman Game in Python

## Project Description

The **Hangman Game** is a classic word-guessing game where players attempt to guess a hidden word by suggesting letters. Each incorrect guess results in losing a life, and the game ends when the player either guesses the word correctly or runs out of lives.

This project is implemented in Python and includes a word list and ASCII art representation of the hangman stages.

## How to Play

1. **Start the Game**: Run the script in your terminal or IDE:
   ```bash
   python hangman.py
   ```

2. **Guess a Letter**: The program will display blanks representing the hidden word. Type a letter and press Enter.

3. **Correct or Incorrect Guess**:
   - If the letter is in the word, it will be revealed in the correct position.
   - If the letter is incorrect, you lose a life and the hangman drawing progresses.

4. **Winning or Losing**:
   - If you correctly guess all letters, you win! 🎉
   - If you run out of lives, you lose, and the correct word is revealed.

## Example Usage

```
_ _ _ _ _ 
Guess a letter: e
_ e _ _ _ 
Guess a letter: a
You guessed 'a', that's not in the word. You lose a life.
```

## Requirements

- Python 3.x
- `hangman_words.py` (word list)
- `hangman_art.py` (ASCII art)

## Conclusion

Enjoy this fun and interactive **Hangman Game**! Feel free to modify the word list, improve the UI, or add more features.

---

**Developed by Gargi Mishra**(www.linkedin.com/gargi510) – Have fun playing Hangman! 🎉
