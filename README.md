# Trebuchet Ballistic Analysis – MATLAB

## Overview

A MATLAB-based ballistic analysis and simulation project developed for MECH 202 Engineering Computer Applications.

The program simulates a two-player medieval trebuchet game in which the player attempts to launch projectiles at a target building while accounting for projectile launch conditions and wind effects.

## Project Features

- Two-player MATLAB game
- Projectile trajectory calculation
- Variable launch velocity
- Variable launch angle
- Variable trebuchet height
- Random wind speed and direction
- Wind-induced horizontal acceleration
- Graphical projectile trajectory
- Target building visualization
- Hit, near-miss, and miss detection
- Target health tracking
- Turn counter
- Game-over condition

## Engineering Analysis

The target building is modeled as a circular building with:

- Radius: 10 m
- Height: 3 m
- Initial health: 100 HP

Damage is determined by projectile impact:

- Direct hit: -25 HP
- Miss within 5 m: -10 HP
- Other miss: no damage

The game continues until the target building reaches 0 HP or below. 

## MATLAB Skills Demonstrated

- MATLAB scripting
- User input
- Functions
- Random number generation
- Conditional statements
- Loops
- Projectile-motion calculations
- Data visualization
- Plot annotation
- Game-state tracking

## Results

The program generates a graphical representation of each projectile trajectory and the target building, allowing the player to evaluate the outcome of each shot. 

### Example Trajectory

<img width="805" height="542" alt="image" src="https://github.com/user-attachments/assets/5a98e06e-01cf-468b-8ea7-30cf4fa6da1e" />

### Example Gameplay

<img width="857" height="668" alt="image" src="https://github.com/user-attachments/assets/e215d81d-e4b4-4a61-a775-f22afb124442" />
<img width="818" height="504" alt="image" src="https://github.com/user-attachments/assets/a84e8113-78de-414a-95a1-ad720bf1de1c" />

## Files

- `Khamchai_Project2.m` – Main MATLAB program
- `wind_function.m` – Wind acceleration function (This file won't be upload due to copyright)
