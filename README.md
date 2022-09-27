# Mazedorado Game Engine

A multiplatform 2D game engine for making 2D RolePlaying games. It's being written in C++, SDL and Lua

<img src="https://import.cdn.thinkific.com/167815/DpCBDm9SYqJ5yRYbvZZ9_tank_small_gif" alt="Game engine ECS C++ Lua" width="320"/>

## Dependencies

- C++ 17
- SDL2 (image, truetype fonts, sound etc)
- GLM
- Lua
- Deal ImGUI

## Environment Setup on Ubuntu

```bash
sudo apt install build-essential
sudo apt install libsdl2-dev libsdl2-image-dev libsdl2-ttf-dev libsdl-mixer-dev
sudo apt install liblua5.3-dev
```

## Environment Setup on Mac

```bash
brew install sdl2 sdl2-image sdl2-ttf sdl2-mixer
brew install lua
```

## Environment Setup on Windows

- Install every libraries from `win64_redist` folder
- or download on your own
- Install Visual Studio with C++ support
- Build the project
`

## Credits

- Course at [https://courses.pikuma.com/courses/2dgameengine](https://courses.pikuma.com/courses/2dgameengine)
- Mazhar Ahmed

> NOTE: Makefile will only work in Linux. You can modify to work in other platforms though.
