# Wordler

[![C/C++ CI](https://github.com/bradenn/Wordler/actions/workflows/cworkflow.yml/badge.svg)](https://github.com/bradenn/Wordler/actions/workflows/cworkflow.yml)

This is a command line word guessing game.

## Getting Started

To build the project, use the following command:

```
make
```

Then play the game:

```
./wordler
```

The game will randomly-select a 5-letter word and you have unlimited guesses to get the word right. Each time you guess, if you have a letter that matches the same location as it is in the secret word, it will be revealed to you. However, any letter that does *not* match the secret word's letter at the same location will be displayed as `_`. Good luck!

### Exiting
You may quit at any time by typing the word 'quit' as an attempt.
