# U.S. States Game

Welcome to the U.S. States Game! This is a fun and interactive Python project that helps you learn and memorize the names of all 50 U.S. states. The game is built using the Turtle graphics library and pandas for data handling.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project is designed to test your knowledge of U.S. states. The goal is to correctly identify all 50 states by entering their names. The program will place the state's name on the map as you correctly guess them. If you exit before guessing all the states, a CSV file will be generated listing the states you missed, so you can learn them later.

## Features
- Interactive map to guess the U.S. states.
- Keeps track of correctly guessed states.
- Generates a list of states to learn if you exit before completing the game.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aaryan505/U.S-STATES-GAME.git
2. **Navigate to the project directory:**
   cd us-states-game
3. **Install the required dependencies:**
   pip install pandas turtle
4. **Run the game:**
   python main.py
## How to Play
1.)The game will display a blank map of the U.S.
2.)A prompt will appear asking for the name of a U.S. state.
3.)Enter the name of the state you want to guess.
4.)If you guess correctly, the state's name will appear on the map in the correct location.
5.)The game will continue until you guess all 50 states or choose to exit.
6.)f you exit early, a CSV file named states_to_learn.csv will be created with the list of states you missed.
## Project Structure
U.S. States Game/
│
├── 50_states.csv              # CSV file containing state names and coordinates
├── blank_states_img.gif       # Image file for the blank U.S. map
├── main.py                    # Main game script
└── states_to_learn.csv        # Generated file with states to learn (if applicable)
## Contributing
Contributions are welcome! If you'd like to improve the game, feel free to fork the repository, make your changes, and submit a pull request.
# License
This project is licensed under the MIT License - see the LICENSE file for details.
https://github.com/aaryan505/U.S-STATES-GAME/blob/main/LICENSE
