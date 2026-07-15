# Asteroid Game

A classic arcade-style Asteroid clone game built with Python and Pygame. Navigate your spaceship through a hazardous asteroid field, shoot down incoming asteroids, and survive for as long as you can!

## Description
This repository contains a full single-player Asteroid game. The player controls a triangular spaceship that can rotate, move forward, and shoot lasers to destroy oncoming asteroids. When shot, larger asteroids split into smaller ones, increasing the difficulty and intensity of the game. If an asteroid collides with the spaceship, it's game over!

## Features
- **Fluid Movement:** Realistic spaceship controls with smooth rotation and forward acceleration.
- **Shooting Mechanics:** Fire shots with a built-in cooldown timer to prevent rapid-fire spam.
- **Dynamic Asteroids:** Large asteroids split dynamically into smaller fragments when hit by shots.
- **Collision Detection:** Precise circle-based collision checking between shots, asteroids, and the player.
- **Clean Architecture:** Modular code design separating components like Player, Asteroid, AsteroidField, Shot, and CircleShape.

## Controls
- **A / D:** Rotate the spaceship left or right.
- **W:** Move the spaceship forward.
- **Spacebar:** Fire shots/lasers.

## How to Run / Installation
1. Ensure you have Python 3.10+ installed.
2. Install the required dependencies (Pygame) via pip:
   ```bash
   pip install pygame
   ```
3. Run the game by executing the main script:
   ```bash
   python main.py
   ```
