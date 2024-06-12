# Number Guessing Game

## Description

This is a simple number guessing game written in C++. In this game, the computer randomly selects a number between 1 and 100, and the player has to guess the number. The game provides hints such as "too high" or "too low" to help the player guess the correct number.

## How to Play

1. The computer will randomly select a number between 1 and 100.
2. The player will be prompted to guess the number.
3. After each guess, the game will provide a hint:
   - "Too low! Try again." if the guess is lower than the target number.
   - "Too high! Try again." if the guess is higher than the target number.
4. The game continues until the player guesses the correct number.
5. The game will display the number of attempts taken to guess the correct number.

## Requirements

- C++ compiler (e.g., g++, clang++)
- Terminal or command prompt

## Installation

1. Clone the repository or download the source code from 
2. Open a terminal or command prompt and navigate to the directory containing the source code.

## Compilation

To compile the program, run the following command:

```bash
g++ -o number_guessing_game number_guessing_game.cpp
