# Speed Typing Test (Python - Curses)

A console-based Speed Typing Test using Python's `curses` library that measures Users' typing speed in real-time and displays WPM dynamically.

## How It Works

- Displays a random sentence for the user to type.
- Captures user keystrokes instantly and compares with the target text.
- Highlights correct characters in cyan and mistakes in red.
- Calculates Words Per Minute (WPM) as the user types.
- Ends test when the user completes the text or presses ESC.

## How to Run

1. Make sure Python 3 is installed on your system.
2. If you are on Windows, install the `windows-curses` package by running:
pip install windows-curses
3. Clone or download this repository.
4. Place a text file named `text.txt` in the same directory with some sample sentences (one per line).
5. In your terminal, run the program with:
python project.py
6. Follow on-screen prompts to begin typing and see your typing speed.

## What I Learned and Used

- Using Python's `curses` for terminal-based UI and color handling.
- Real-time input capture and display without blocking.
- Dynamic calculation of WPM from character count and elapsed time.
- Comparing user input against target text and highlighting typos.
- Managing control keys like backspace and escape.
- Integrating file I/O to load typing prompts.

## Skills Used

Python, Curses Library, Terminal UI, Real-time Input Handling, File I/O, Text Processing, CLI Interaction
