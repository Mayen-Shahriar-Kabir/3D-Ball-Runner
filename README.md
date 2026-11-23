# 3D Ball Runner

A 3D endless runner game built using Python and OpenGL. The player controls a rolling ball navigating through a dynamically generated obstacle course. The game features progressive difficulty, interactive camera modes, special abilities, and various collectibles.

## 🎮 Game Features
* **Dynamic Movement & Progressive Difficulty:** The ball automatically rolls forward, with its speed gradually increasing over time to raise the difficulty. 
* **Special Abilities:** Players can jump over low obstacles, use a spin attack to destroy specific chasing enemies, or shrink the ball to dodge tight spaces.
* **Camera Controls:** Toggle between a first-person (behind the ball) and third-person view. The camera automatically tilts when the ball jumps, and players can manually adjust the height and rotation.
* **Diverse Obstacles:** Dodge stationary cubes, moving cylinder walls, tall cylinders, growing/shrinking cubes, and a special red cylinder that actively chases the player.
* **Cheat Mode:** A toggleable shield mode that provides permanent invincibility against obstacles.
* **Game Over Mechanics:** When lives reach zero, the ball visually compresses and turns black. Players can instantly restart the run.

## 🪙 Power-Ups & Collectibles
Collect colored spheres to boost your score and survivability:
* **Yellow Coins:** Normal coins that grant +5 to your score.
* **Green Coins:** Grants an extra life (up to a maximum of 5).
* **Pink Coins:** Grants extra spin attack power.
* **Orange Coins:** Provides a temporary 2x speed boost.
* **Blue Coins:** Activates a temporary shield for invincibility against obstacles.

## ⌨️ Controls
* **A / D:** Move Left / Right
* **Spacebar:** Jump
* **F:** Spin Attack (destroys the red chasing cylinder)
* **S:** Shrink the ball temporarily
* **C:** Toggle Cheat Mode (Invincibility)
* **R:** Restart Game
* **Right Mouse Click:** Toggle First-Person / Third-Person Camera
* **Up / Down Arrows:** Adjust Camera Height
* **Left / Right Arrows:** Rotate Camera

## 🛠️ Team & Contributions
This project was developed by:
* **Anirban Saha:** Initial environment setup (track, sky, clouds), basic player movement, stationary/moving obstacles, scoring base, and game-over mechanics.
* **Suhana Ahmed:** Jumping mechanics, collectible coins, power-ups, and cheat mode implementation.
* **Mayen Shahriar Kabir:** Spin attack, shrink feature, progressive speed system, dynamic camera features, and complex/chasing obstacles.

## 🚀 How to Run
**Prerequisites:** Python 3.x and PyOpenGL (`pip install PyOpenGL PyOpenGL_accelerate`).

Run the game from your terminal:
```bash
python 3D_Ball_Runner.py
