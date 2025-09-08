# Tomino - Technical Interview

A Unity-based Tetris game project for technical programming interviews.

## Interview Tasks

### Task 1: Fix Compilation Errors
Fix all compilation errors in the project to ensure it builds and runs properly.

### Task 2: Set Game Window to iPhone 12 Portrait Mode
Configure Unity editor's Game window to iPhone 12 portrait resolution for mobile testing.

### Task 3: Fix Pause Menu Display Issue
Fix the pause menu not displaying when the pause button is clicked.

### Task 4: Add New Tetris Shape
Add a new tetris piece shape to the game. The traditional Tetris game has 7 classic shapes (I, O, T, S, Z, J, L).

**Requirements:**
1. Design a new balanced and interesting shape
2. Define shape data in the appropriate code files
3. Integrate with game systems:
   - Normal spawning and falling
   - Proper rotation mechanics
   - Collision detection compatibility
   - Line clearing logic participation

### Task 5: Implement Piece Rotation
Implement clockwise rotation logic in the `RotatePiece()` method in `Assets/Tomino/Script/Model/Board.cs` at line 188 where the `// todo:rotate` comment is located.

### Task 6: Implement Line Clearing
Implement the line clearing functionality when rows are completely filled.

**Requirements:**
1. Detect full rows across the game board
2. Remove all blocks in full rows
3. Move blocks above cleared rows downward
4. Return the number of cleared rows for scoring

### Task 7: Optimize Android Package Size
Optimize the game's images, sounds, and other resources to reduce Android package size.

**Requirements:**
1. Analyze current assets (images, audio, textures)
2. Apply optimizations: compression, format changes

## Screenshots

<table>
  <tr>
    <td width="375">
      <img src="https://user-images.githubusercontent.com/1027098/66525860-2203b200-eaf7-11e9-9416-cf8c952ecb2c.gif"/>
    </td>
    <td width="375">
      <img src="https://user-images.githubusercontent.com/1027098/66526292-6e032680-eaf8-11e9-9720-3e3189cdeb43.jpg"/>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="https://user-images.githubusercontent.com/1027098/66526261-55930c00-eaf8-11e9-9f9f-cc21ffad3e8b.png"/>
    </td>
  </tr>
</table>