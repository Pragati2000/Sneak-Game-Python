# Description:
Sneak 2D Game is a stealth-based game where players navigate through levels while avoiding detection from enemies. Developed using Python, the game combines the Tkinter library for the graphical user interface and the random module to add unpredictability to enemy movements and obstacles. The project is designed to be developed in Visual Studio Code (VS Code).

# Features:
Stealth Gameplay: Sneak past enemies without being detected.

Randomized Elements: Enemy patrol patterns and obstacle placements are randomized for a unique experience each time.

Tkinter GUI: The game uses Tkinter for 2D graphics and simple interface design.

Multiple Levels: Levels with increasing difficulty and new challenges.

Easy Controls: Simple keyboard controls using arrow keys.

# How to Set Up in Visual Studio Code:
  1.Clone the repository to your local machine:
 git clone https://github.com/Pragati2000/Sneak-Game-Python.git
 
  2.Open the project in VS Code:
 Open Visual Studio Code.
 Click on File > Open Folder and select the folder where you cloned the repository.
 
  3.Install Required Libraries:
  Open a terminal in VS Code (Ctrl + ) and run the following command to install Tkinter (if not already installed):
    sudo apt-get install python3-tk
  For Windows and Mac users, Tkinter comes pre-installed with Python.
  If you need to install Pygame as well for additional game elements, use:
    pip install pygame
    
  4.Run the Game:
  Open main.py in VS Code.
  Run the game by clicking Run > Start Debugging or pressing F5.

# How to Play:
Start the game: The snake starts as a short line, often with a few blocks or segments. Food is placed randomly on the screen.

Control the snake's direction: You change the direction of the snake using the arrow keys. The snake continuously moves forward in the direction you set.

Eat food to grow: When the snake touches a food item, the snake grows longer, and a new piece of food appears somewhere else on the screen.

Avoid collisions: As the snake grows, it becomes harder to avoid colliding with its own body. The game ends if you crash into a wall or run into yourself.

# Screenshots
![Screenshot 2024-10-01 122851](https://github.com/user-attachments/assets/01a41d58-6e44-4cf8-a282-5c321ab63483)

# Active game screen
![Screenshot 2024-10-01 124050](https://github.com/user-attachments/assets/a1daa355-7fca-4b0c-a497-cc1d58645c0f)

# Game over screen
![Screenshot 2024-10-01 124113](https://github.com/user-attachments/assets/d5791261-26ef-415d-bfb8-777aad7a38f6)

# Key Concepts and Code Structure:
  Tkinter: 
 Used for rendering the game window and creating basic 2D graphics.
    The game screen is created using Tkinter’s Canvas widget, which handles all the drawings.
    
   Random Module: 
 Adds randomness to the game:
    Enemy movement patterns and obstacle placements are generated using random.randint() to add unpredictability to gameplay.
  
  Game Loop: 
 Implemented using Tkinter's after() method to continuously update the game state, including character movement and enemy behavior.

# Developing in VS Code:
   # Debugging: 
  Set breakpoints in VS Code for debugging and testing random enemy behaviors or any Tkinter-related issues.
  
   # Code Formatting: 
  Use extensions like Pylint for code formatting and linting

# Technologies Used:
Python: Core programming language for game development.

Tkinter: For GUI and game window rendering.

random module: For generating random enemy movements and obstacles.

VS Code: The IDE used for development, debugging, and testing.



