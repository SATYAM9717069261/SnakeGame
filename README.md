🐍 2D Snake Game in Rust
A classic 2D Snake Game implemented in Rust using the Piston game engine. Eat food, grow the snake, and avoid collisions with walls or yourself!


🎮 Game Rules
Controls: Use arrow keys (↑ ↓ ← →) to move the snake.

Objective: Eat the red square (food) to grow longer.

Game Over Conditions:

The snake hits any border.

The snake runs into its own body.

Restart: Game restarts automatically after 1 second when over.

🧠 Features
Written in Rust with the Piston game engine.

Collision detection (walls and body).

Simple, minimal interface.

Automatic game reset after game over.

🛠️ Requirements
Rust
Piston dependencies

📁 Project Structure
src/
├── main.rs        # Game loop and window handling
├── game.rs        # Game state and logic
├── snake.rs       # Snake movement and collision
├── draw.rs        # Rendering logic
Cargo.toml         # Dependencies and metadata


📦 Dependencies (Cargo.toml)
[dependencies]
piston_window = "0.127.0"
rand = "0.8"

<img width="522" height="557" alt="image" src="https://github.com/user-attachments/assets/a4d64e05-0965-4fdd-aeec-51581cc8e30c" />

