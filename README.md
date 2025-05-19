# tetris
Java Tetris using a tile‐engine and bag randomizer

Tetris

**A Java implementation of Tetris** using a tile‐based engine and the “bag” randomizer.

## Features

- **Tile engine**  
  Renders a grid of `TETile` objects via `TERenderer`.  
- **Tetromino logic** (`Tetromino.java`)  
  Defines all seven shapes, rotation, and block coordinates.  
- **Bag randomizer** (`BagRandomizer.java`)  
  Guarantees each 7‐piece cycle before repeats.  
- **Movement & controls** (`Movement.java`)  
  Handle left/right/down shifts, rotations, and hard drop.  
- **Game loop** (`Tetris.java`)  
  Spawns new pieces, clears completed rows, tracks score, and detects game over.  
- **Utility classes**  
  - `RandomUtils.java`, `FileUtils.java` for pseudo-random seed & I/O  
  - `Tileset.java` holds the tile constants (colors, images)  


