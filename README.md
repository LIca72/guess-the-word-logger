# guess-the-word-logger
# 🔤 Guess the Word — Logger Edition

A simple Python word guessing game with error handling and logging.

---

## 🎯 Description

This program lets the user guess a secret word.  
If the input is invalid (e.g. numbers, empty input), an error is raised, shown, and **saved to a log file** (`log.txt`).

---

## 💡 Features

- Secret word to guess
- User input with validation (`isalpha`)
- Error handling with `try-except-finally`
- Logs all input errors to `log.txt`
- Case-insensitive guessing

---

## 🧪 Example

```bash
Guess the word: 123
Something went wrong: Invalid input: only letters allowed
Try again!

Guess the word: python
Yes! You guessed it!
Program finished.
