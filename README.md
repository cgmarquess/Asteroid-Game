<div align="center">
  
  [![Português](https://img.shields.io/badge/Português-green)](README.pt-br.md)

</div>

# 2D Space Shooter Engine (Asteroids Clone)

A high-performance 2D game engine built from scratch with **Pure Java**, recreating the classic mechanics of "Asteroids".

The goal of this project was not just to create a game, but to **implement a vector-based physics system from scratch**, studying fundamental concepts of computer graphics, linear algebra, and real-time memory management.

![Game Demo](demo.gif)

## Engineering & Mathematics

Unlike games built with commercial engines (Unity/Godot), all physics and rendering logic were manually implemented:

* **Custom Vector Physics:** Manual implementation of vectors for calculating velocity, acceleration, inertia, and angular rotation. No pre-built physics libraries were used.
* **Collision Detection:** Geometry-based algorithms (polygons) to detect interactions between the ship, asteroids, and projectiles.
* **Active Game Loop:** Utilization of JavaFX's `AnimationTimer` to create a stable 60 FPS rendering loop, decoupling update logic from draw logic.
* **Object-Oriented Design:** Extensive use of Polymorphism to manage the lifecycle of game entities (Enemies, Player, Projectiles).

## Tech Stack

* **Java 21** (Core Language)
* **JavaFX 21** (Graphics Rendering & Keyboard Input)
* **Design Patterns:** Game Loop, Component Pattern.

## Features

* **Newtonian Movement:** The ship possesses inertia and acceleration, simulating movement in a vacuum.
* **Wrap-around Mechanics:** Entities leaving one side of the screen reappear on the opposite side (modular coordinate calculation).
* **Progressive Difficulty:** Gradual increase in complexity over time.
* **Particle System:** Visual feedback for collisions and destruction.

## How to Run

### Prerequisites
* Java JDK 21 installed.
* IDE (IntelliJ IDEA or Eclipse) configured with JavaFX support.

### Steps
1.  Clone the repository:
    ```bash
    git clone https://github.com/cgmarquess/Asteroid-Game.git
    ```
2.  Open the project in your IDE.
3.  Locate the main class and configure the run configuration.
4.  Run the `main` method.

Developed by [Gabriel Marques] - [[LinkedIn](https://www.linkedin.com/in/cgmarquess/)]
