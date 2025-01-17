# CUB3D
This project serves as an introduction to graphical programming and game development concepts. By implementing raycasting, Cub3D renders a 2D map to appear as a 3D environment from the player's perspective, similar to early first-person shooter games.

## USAGE
Clone the Repository:

```bash
git clone https://github.com/jasonmgl/cub3d.git
```
Navigate to the Directory:

```bash
cd cub3d
```
Compile the Program:

Use the provided Makefile to compile the project:

```bash
make
```
This will generate the executable cub3d.

Run the Program:

Execute the program with a map file as an argument:

```bash
./cub3d maps/your_map.cub
```
Replace your_map.cub with the path to your desired map file.

## DEPENDENCIES
- Compiler: Requires a C compiler like gcc.
- Make: Utilizes make for building the project.
- Libraries: Depends on the MiniLibX library for graphical rendering. Ensure that MiniLibX is properly installed on your system.

## DESCRIPTIONS
Includes: Contains header files defining function prototypes and necessary macros.

Lib: Includes the libft library, providing essential utilities for string manipulation, memory management, and linked list operations.

Maps: Houses map files used by the program to render different environments.

Sound: Contains audio files for in-game sounds.

Srcs: Holds the source code for the main functionalities of the program, including initialization, rendering, and event handling.

Srcs_bonus: Includes additional features and enhancements beyond the basic requirements.

Textures: Stores texture files used for rendering walls, sprites, and other graphical elements.

with @ysengoku.
