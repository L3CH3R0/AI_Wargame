# README for AI Wargame Python Script
## Overview
This Python script is a strategic game simulator where players engage in a grid-based wargame, either as an Attacker or a Defender. The game features AI components, units with various types and abilities, and implements sophisticated game mechanics like health modification, movement rules, and combat strategies.

## Features
Unit Types & Players: Defines various unit types (AI, Tech, Virus, etc.) and two player roles (Attacker, Defender).
Game Mechanics: Includes functions for unit health management, movement, and combat.
Coordination System: Utilizes a coordinate system for gameplay on a grid.
Game Options & Statistics: Customizable game settings and tracking of game statistics.
Minimax Algorithm: Implements Minimax algorithm for decision-making, with variations in heuristic evaluation.
## Usage
Run the script and follow the prompts to configure the game (game type, turns, time limit, etc.).
Input moves in a specific format (e.g., A1 B2) to play the game.
The script supports different modes of play, including human vs. AI, AI vs. AI, etc.
## Dependencies
Python 3
requests library for HTTP requests (if using a game broker).
