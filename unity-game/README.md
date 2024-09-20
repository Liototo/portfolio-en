# "Human-computer interaction" project: Unity game

Developed by Eliott Bell, Victor Faltings and Belén Gómez García

Bachelor, semester 4 (feb. 2022 - jul. 2022), EPFL (Ecole Polytechnique Fédérale de Lausanne)

This project consisted of three steps:

- Developing a predetermined game mode ("classic" mode) from provided resources, following precise instructions
- Implementation of predetermined improvements to said game mode without clear instructions
- Creation of our own game mode ("maze" mode) without any instructions or constraints

The game is playable with a keyboard or with Cellulos, which are hexagonal robots with haptic feedback created at EPFL. Playable characters are modelled after said robots.

You can play the game by launching compiled-game/SpaceGhostSheep.exe or read the source code in the unity-project/ folder.

### What we did

The code we wrote is in the unity-project/Assets/Scripts/ folder. We wrote most of the C# files in the Core/Behaviors/, Game/, Maze Game/, Menu/ and UI/ folders, as well as the PlayerMovement.cs file. In the unity-project/Assets/Resources/ folder, the GemCollected.wav and PointStolen.wav sound effects were also composed by yours truly.

### Developed skills

- Game development on Unity

- C# programming

- UI design

- Teamwork and organisation

## Gallery

The "classic" game mode, implemented following precise instructions. The two players (blue and magenta) must push the robot (green) in the center zone to earn points; regularly, the green robot turns red and starts chasing the players, making them lose points on impact.
<p align="center"><img src="..\Resources\sgs_classic.png" width="50%"></p>

The "maze" game mode, designed by our team. The two players must pick up gems (green, pink or orange), then go through the center zone before returning to their base to earn points. If the players collide, they swap held gems.
<p align="center"><img src="..\Resources\sgs_maze.png" width="50%"></p>

A harder version of the "maze" game mode, where the labyrinth is almost entirely dark.
<p align="center"><img src="..\Resources\sgs_maze_hard.png" width="50%"></p>
