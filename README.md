# Cub3D

Cub3D is a graphical project developed in C that simulates a simple 3D rendering engine using "raycasting" (similar to Wolfenstein 3D). It allows you to explore 2D environments with a three-dimensional view.

## Project Structure
- **src/**: main source files (parsing, rendering, raycasting, input handling, etc.)
- **inc/**: header files (function and data structure definitions)
- **libft/**: personal utility library
- **minilibx/**: graphics library for window management and rendering
- **maps/**: example maps in `.cub` format
- **wav/**: audio files and timing data
- **xpm/**: textures in XPM format

## Requirements
- Linux system
- C compiler (gcc)

## How to Compile and Run

1. Open the terminal in the main project folder.
2. Run the command:
   ```sh
   make
   ```
   The Makefile will automatically fetch and build all required libraries.
3. Start the program:
   ```sh
   ./cub3d
   ```

## License
Clone. Have fun.