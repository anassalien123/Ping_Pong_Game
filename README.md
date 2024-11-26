# Ping_Pong_Game

---

This project is a simple **Ping Pong Game** created using Python's `turtle` module. It's a two-player game where players control paddles to hit a moving ball, scoring points when the opponent misses the ball.

## Features

- **Interactive Gameplay**: 
  - Player 1 controls their paddle using the `W` (up) and `S` (down) keys.
  - Player 2 uses the `Up Arrow` (up) and `Down Arrow` (down) keys.
- **Real-Time Scoring**:
  - Scores are displayed at the top of the screen and updated live.
- **Dynamic Ball Movement**:
  - The ball bounces off paddles and walls, reversing its direction upon collision.
- **Clean Visual Design**:
  - Minimalist black background, with white ball and central divider.
  - Blue and red paddles for easy player differentiation.

## How It Works

- The game window is initialized with dimensions of `800x600` pixels.
- A ball moves continuously in random directions, bouncing off walls and paddles.
- If the ball passes a paddle, the opposing player scores a point.
- The game continues indefinitely, tracking the players' scores.

## Controls

| Player | Action | Key         |
|--------|--------|-------------|
| Player 1 | Move Up  | `W`         |
| Player 1 | Move Down| `S`         |
| Player 2 | Move Up  | `Up Arrow`  |
| Player 2 | Move Down| `Down Arrow`|

## Setup & Execution

1. Ensure you have Python installed on your system.
2. Save the script as `ping_pong_game.py`.
3. Run the script using:
   ```bash
   python ping_pong_game.py
   ```
4. Enjoy playing with a friend!

## Game Preview

A simple interface with moving ball, two paddles, and real-time scoring:

- **Left Player (Blue Paddle)** vs **Right Player (Red Paddle)**
- A central white divider separates the field.
- Dynamic ball movement and paddle interactions.

---
![image](https://github.com/user-attachments/assets/51c887c9-f51d-466e-b0ea-e9821a0b2917)
