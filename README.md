# PongGame
```markdown
A simple Pong game built using the Kivy framework in Python. This game simulates the classic Pong game where two players control paddles to hit the ball back and forth.

## Features

- Two-player paddle control
- Ball movement and bouncing
- Scoring system

## Prerequisites

- Python 3.6+
- Kivy 1.0.9+

## Installation

1. **Clone the repository:**

```sh
git clone https://github.com/Saikrishnaz/PongGame.git
cd pong-game
```

2. **Create and activate a virtual environment (optional but recommended):**

```sh
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. **Install the required dependencies:**

```sh
import kivy
from kivy.app import App
from kivy.uix.widget import Widget
from kivy.properties import (NumericProperty,ReferenceListProperty,ObjectProperty)
from kivy.vector import Vector
from kivy.clock import Clock
from random import randint
```

## Running the Game

1. **Ensure you have both the `main.py` and `pong.kv` files in the project directory.**
2. **Run the game:**

```sh
python main.py
```

## File Structure

- `main.py`: The main Python script that contains the game logic.
- `pong.kv`: The Kivy language file that defines the UI layout.

## Controls

- Player 1 (left paddle): Move the mouse or touch the left side of the screen to control.
- Player 2 (right paddle): Move the mouse or touch the right side of the screen to control.

## Screenshots

![Pong Game Screenshot](![image](https://github.com/user-attachments/assets/6ede9852-f400-43f4-a986-f5af08731fef))

## Acknowledgements

- [Kivy](https://kivy.org/) - Open source Python library for rapid development of applications.
```

You can customize the repository URL, add any additional sections, and include a screenshot of your game for the `Screenshots` section. If you have a license file, ensure it's referenced correctly in the `License` section.
