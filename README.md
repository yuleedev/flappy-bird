# Flappy Bird

Remake of Flappy Bird, made in Godot 4.5. Wanted some practice with making sidescrollers and this one's a classic. :)

## Getting Started/Installation

1. Download and install [Godot 4.5](https://godotengine.org/download).
2. Clone this repository:
   ```bash
   git clone https://github.com/yuleedev/flappy-bird.git
   ```
3. Open Godot, click **Import**, and select the `project.godot` file in the cloned folder.
4. Press **F5** (or the Play button) to run the game.

## Controls

- **Left Mouse Button:** Start the game and flap.
- **Restart Button:** Click to play again after a game over.

## How to Play

- Click to start. The bird takes off and pipes begin scrolling in.
- Click to flap and keep the bird in the air. Gravity pulls it down between flaps.
- Fly through the gap between each pair of pipes to earn a point.
- The game ends if the bird hits a pipe, hits the ground, or flies above the top of the screen.

## Project Structure

- `scenes/`: Game scenes and scripts (main, bird, pipe, ground).
- `assets/`: Sprites for the bird, pipes, ground, background, and restart button.
- `game_over.gd`: Game over screen and restart signal.
