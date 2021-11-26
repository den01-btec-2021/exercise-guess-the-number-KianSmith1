[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6454519&assignment_repo_type=AssignmentRepo)
# Exercise - Computer guess the number

Implement a program in Python which guesses a random number that the computer has chosen.

**Hints:**

- Use the string `"I guessed " + str(guess) + "."` when outputting the computer's guess.
- Input the string `You got it right!` when the answer is right.
- Input the string `Too high!` when the guess is too high.
- Input the string `Too low!` when the guess is too low.

You might find the following helpful:

```plaintext
user thinks of random number (no coding here!)

loop until the computer gets it right
    computer guesses random number

    if the guess is right
        user inputs yes
    otherwise
        if the number is too low
            user inputs higher
        if the number is too high
            user inputs lower
```

Implement the program so that the following issues are fixed:

- Tell the computer what *higher* and *lower* means.
- Don't let the computer guess the same answer twice.

**Note:** *There is no automatic testing for this exercise - you are responsible for writing and running your own tests!*
