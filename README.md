#### MAZE PROJECT

This is my final ALX Software Engineering foundations project.

It is a 3D maze raycasting game developed with SDL2 library and C.

Simple DirectMedia Layer (SDL) is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games

#### INSTALLATION
```sh
$ git clone https://github.com/joeotine/Maze_Project.git
```
#### TECHNOLOGY STACK
- SDL2 Library (To display graphics in the window)
- C Programming Language
- upng (To decode the images)

#### PROJECT STRUCTURE

```
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
```

#### FLOWCHART

![The Maze Flow Chart](https://i.imgur.com/GRM5v9E.png)

#### DEVELOPMENT SETUP

- For debian based linux os  sudo apt-get install libsdl2-dev

#### COMPILATION

`make`

#### EXECUTION

`./maze`

#### USAGE

- Use up and down arrow keys to move farward and back (keys W and S perform the same function)
- Use right and left arrow keys to turn the camera around (keys A and D perform the same function) 

#### AUTHOR

- Joseph Otine - joeotine@gmail.com
