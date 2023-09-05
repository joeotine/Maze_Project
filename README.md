#### MAZE PROJECT

For my final foundations project, I did and submitted this. It is a 3D maze raycasting game developed
with SDL2 library and C.

#### TECHNOLOGY STACK
- SDL2 Library (To display graphics in the window)
- C Programming Language
- upng (To decode the images)

#### PROJECT STRUCTURE

 ├── README.md
 |── Makefile
 ├── src
 │   ├── graphics.c         
 |   ├── textures.c  
 |   |── ray.c  
 |   ├── player.c  
 |   ├── main.c  
 │   ├── wall.c
 │   ├── sprite.c 
 │   ├── map.c 
 │   └── upng.c
 └── headers
     ├── graphics.h
     ├── textures.h
     ├── ray.h
     ├── player.h
     ├── wall.h
     ├── sprite.h
     ├── upng.h
     ├── map.h

#### DEVELOPMENT SETUP

- https://lazyfoo.net/tutorials/SDL/01_hello_SDL/linux/index.php

For debian based linux os  sudo apt-get install libsdl2-dev

#### COMPILATION

`make`

#### EXECUTION

`./make`

#### USAGE

- Use up and down arrow keys to move farward and back
- Use right and left arrow keys to turn the camera around

#### AUTHORS

- Joseph Otine - joeotine@gmail.com
