https://github.com/user-attachments/assets/fbe36a0d-df1c-44af-b9a0-4c8a982aeb63
# Gravitational Slingshot Effect Simulation
This is a gravity-based space simulation where you control the trajectory of a spacecraft by tinkering with the gravitational force of a planet. The game allows you to visualize the gravitational slingshot effect, which is used in real-world space missions for altering spacecraft velocities. You can adjust the initial velocity and direction of the spacecraft using mouse clicks and observe how gravity affects its motion around the planet.


# Features
1. Realistic Gravity Simulation: The game simulates gravitational forces between a planet and a spacecraft based on Newton's Law of Universal Gravitation.
2. Customizable Launch Trajectories: Launch the spacecraft in any direction and see how it reacts to the gravitational pull of the planet.
3. Collision Detection: Spacecraft can collide with the planet or go off the screen.
4. Dynamic Gameplay: The spacecraft's motion is governed by physics, making each launch unique depending on its velocity and angle.

# Prerequisites
To run this game, you need to have the following installed on your system:

1. Python 3
2. Pygame library
You can install Pygame using pip: pip install pygame


# Installation
1. Clone or download the repository to your local machine: https://github.com/Hamadabcn/rocket_simulation.git
2. Ensure that all the image assets (background.jpg and jupiter.png) are in the same directory as the Python script.

# How to Run
1. Open a terminal or command prompt.
2. Navigate to the directory containing the Python script.
3. Run the game using the following command: python main.py

# How to Play
1. Set the Launch Position: Click once anywhere on the screen to set the starting position of the spacecraft.
2. Set the Launch Direction: Click again to set the trajectory and velocity by clicking a second time where you want the spacecraft to head.
3. Observe the Gravitational Pull: The spacecraft will move according to the gravitational pull of the planet located at the center of the screen. You can launch multiple spacecrafts and see how each behaves differently.
4. Collisions and Boundaries: The spacecraft will be removed from the screen if it collides with the planet or exits the screen boundary.

# Controls
1. Mouse Click: Set the starting point and direction for the spacecraft.
2. Close Button: Quit the game.

# Game Mechanics
1. Gravitational Force: The spacecraft is pulled towards the planet using the formula:
F=GMm/r^2
where F is the gravitational force, G is the gravitational constant, and r is the distance between the planet and the spacecraft.

2. Planet and Spacecraft: The planet is located at the center of the screen, and the spacecraft can be launched from anywhere on the screen with customizable velocities based on the mouse clicks.

# Customization
You can customize various parameters in the main.py file:

1. Gravitational Constant (G): Adjust the gravitational pull by changing the value of G.
2. Planet Mass (PLANET_MASS): Modify the mass of the planet to change how strongly it attracts the spacecraft.
3. Ship Mass (SHIP_MASS): Change the spacecraft mass to influence its response to gravitational forces.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
