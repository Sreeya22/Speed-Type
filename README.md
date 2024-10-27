# Speed Typing App

Speed Typing App is a Python-based typing speed test application. This project challenges users to type words displayed on the screen as quickly and accurately as possible. It records the user's typing speed in terms of words per minute (WPM) and accuracy by tracking the number of correct and incorrect entries. This is an interactive app designed with Python's Tkinter library.

## Features
**Real-time Typing Speed Test:** Words appear on the screen for users to type, allowing them to test and improve their typing speed.
**Scoring System:** Tracks the number of correctly typed words (Hits), incorrect words (Misses), and calculates a total score.
**Dynamic Countdown Timer:** A 60-second timer is set for each round, challenging users to type as many words as possible before time runs out.
**Retry Option:** After each round, users can opt to play again and try to beat their previous score.

## How to Play
Launch the app, and you'll see a "Start Typing" prompt and a word displayed on the screen.
Type the word in the entry field and press Enter.
For every correct entry, your score will increase, and a new word will appear.
If you enter the word incorrectly, it will be counted as a "miss."
When the timer reaches zero, a pop-up will display your score, and you can choose to play again.

## Code Structure

Slider Animation: Displays "Speed Typing App" as a scrolling text on top of the app.
Timer Function: Handles the countdown timer, displaying time left and ending the game when time runs out.
Game Logic: Checks typed words for correctness, updates scores, and displays a new word for each correct or missed entry.

## Requirements
1.Python 3.x
2.Tkinter library (comes pre-installed with Python)
3.words.py file containing a list of words for the typing test

## Setup
1.Clone or download this repository.
2.Ensure you have words.py with a list of words for the typing challenge.
3.Run the script using Python:
`python speed_typing.py`

## Dependencies
**Tkinter:** Used for building the GUI.
**Random:** Used for shuffling words in each game session.
