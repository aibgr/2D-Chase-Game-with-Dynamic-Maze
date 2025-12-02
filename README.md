# Penguin Rush – Dynamic Rotating Maze Chase Game

A fast-paced 2D cognitive training game built with Pygame that challenges and improves **processing speed** and **spatial orientation** under rapidly changing conditions.

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![Pygame](https://img.shields.io/badge/Pygame-2.5+-green.svg)](https://www.pygame.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)

## Game Concept & Cognitive Goal

Most maze games are static. This one is not.

You control a **blue penguin** using arrow keys in a maze that **suddenly rotates 90°, 180°, or 270°** multiple times during the run.  
When the board rotates → the meaning of Up/Down/Left/Right instantly changes!

Meanwhile, a ruthless **black penguin (AI opponent)** starts from the same position and races to the fish.  
If it gets there first → **you lose**.

The game directly trains:
- Ultra-fast mental rotation
- Working memory under stress
- Cognitive flexibility & processing speed

Perfect for cognitive training apps, neuroscience experiments, or just addictive fun.

## Features

- Dynamic 90° board rotations at random intervals
- Smart AI opponent with A* pathfinding (very hard to beat!)
- Smooth animations and rotation effects
- Score = time taken (lower = better)
- Win/lose screen with replay option
- Fully commented single-file code (ideal for learning)

## Demo Screenshot
<img width="2000" height="2588" alt="image" src="https://github.com/user-attachments/assets/b081927c-4fd9-4d08-86c3-d119ecb02543" />

## How to Play – 10 Seconds Setup

```bash
git clone https://github.com/aibgr/2D-Chase-Game-with-Dynamic-Maze.git
cd 2D-Chase-Game-with-Dynamic-Maze
pip install pygame
python "Final Code.py"
