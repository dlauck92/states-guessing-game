# U.S. States Game

A fun and interactive U.S. states guessing game using Python and the Turtle module!

## Overview
This project is a simple game where users try to guess all 50 U.S. states. The game utilizes Python's Turtle graphics and Pandas for handling state data.

## How to Play
1. Run the script.
2. A blank U.S. map will appear.
3. Enter the name of a U.S. state in the text prompt.
4. If the guess is correct, the state name appears on the map at its correct location.
5. The game continues until all 50 states are guessed or the user exits.
6. If the user exits before completing, a `states_to_learn.csv` file is generated, listing the states they missed.

## Requirements
- Python 3
- `turtle` (comes with Python)
- `pandas` (install using `pip install pandas`)

## Setup & Execution
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/us-states-game.git
   cd us-states-game
   ```
2. Ensure dependencies are installed:
   ```sh
   pip install pandas
   ```
3. Run the game:
   ```sh
   python main.py
   ```

## Files Included
- `main.py` - The main script to run the game.
- `50_states.csv` - Contains state names and their x, y coordinates.
- `blank_states_img.gif` - The U.S. map used in the game.
- `states_to_learn.csv` - Generated when exiting early, listing missed states.

## Future Improvements
- Add a scoring system.
- Implement a timer for added challenge.
- Support for different regions or countries.

## License
This project is open-source. Feel free to modify and improve it!

