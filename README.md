# THIS IS REALLY REALLY OUT OF DATE! PLEASE FORK IT AND UPDATE IT!
I'm not like super into Zig (that may change once the new Std.IO async stuff gets added cuz that does look sick). 
I made this document a couple of years ago because I was interested in the state of gamedev in Zig. 
I think things are VERY different now, so many of the links lead to dead repos.
P.S For my money, you should probably either use:
https://github.com/Gota7/zig-sdl3
or
https://github.com/gdzig/gdzig
# List of Zig Gamedev Projects

## Open Source Zig Games
https://github.com/holobeat/zig-wasm-snake
- The game of snake implemented in zig and running on webassembly.

https://github.com/fabioarnold/zig-gorillas
- 2-player local multiplayer game. Take turns throwing an exploding banana at each other.

https://github.com/thejoshwolfe/legend-of-swarkland
- Nethack inspired 2D Simple turn-based action fantasy puzzle sandbox.
- rougelike

https://github.com/mlarouche/ZigWwiseDemo
Discord tag of creator: BaroqueLarouche#7469
- Sample Application that uses Dear IMGUI, Win32, Direct3D 11 and Audiokinetic Wwise in Zig. 
- all of which are quite popular in game development.

https://github.com/musi-musi/musi-leko/
Discord tag of creator: jadebot#5200
- voxel-base (think minecraft) style engine
- early in development
- made with zig 0.9

https://github.com/JustinRyanH/znake
Discord tag of creator: JustJustin#5998
- Multiple implementations of snake in using zig
- Has a WASM4 implementation, Has a sokol-zig implementation
- Implements prime31's `zig-ecs` for the sokol version

https://github.com/PixelGuys/Stella-Dei
Discord tag of creator: Zen1th#3854
- SimEarth-like sandbox game where you can make and thrive your very own randomly-generated planet
- uses zalgebra, zigimg, zig-opengl, Zig-Tracy and mach-glfw

## Zig Game Frameworks

https://github.com/JonSnowbd/slingworks
Discord Tag of creator: Aetherwind#8836
- missing a few things like gamepad support, but now has a wiki for basic tutorials, and an example game(in development) that shows how to use the various features
- Slingworks is a 2d Game Engine where you provide the types, and slingworks does all the leg work for generating an editor, and all the windowing/graphics for you, and organized into Entity based scenes that has serialization saving/loading managed for you.
- Note: currently recommened to use the dev branch instead of master

https://github.com/prime31/zig-gamekit
- bundled along with zig renderkit, seems to be focused on 2d graphics only
- uses SDL2 as its only (!) dependency.

https://github.com/prime31/zig-renderkit
- core library of zig-gamekit

website: https://hexops.com/mach
github: <https://github.com/hexops/mach>
- Mach engine is still in very early stages though it's improving rapidly.
- Aims to be an all-in-one game engine made in Zig
- Inspired by Bevy and Our Machinery.

There's also https://github.com/MasterQ32/zero-graphics (from @xq#5894 on Discord) 
- zero-graphics is best at cross-platform 2D / light 3D stuff. 


https://github.com/michal-z/zig-gamedev
Discord Tag of creator: michalziulek#4304
- 3D zig framework. Can already do some very impressive stuff, including ray tracing
- The farthest along project in the ecosystem 

https://github.com/Kiakra/Alka
Discord Tag of creator: Kiakra#2810
- Game engine written in zig, compatible with zig version 0.8.0.
- This engine does provide a toolset for you but generally you have to implement how they work and how should be.
- Has an ECS

https://github.com/leroycep/seizer
Discord Tag of Creator: geemili#6637
- a Zig library for making games that target the desktop and browser. It exposes an OpenGL ES 3.0 rendering context and cross platform file loading functions.
- Has an example game here: https://github.com/leroycep/2021-7drl/

https://github.com/zenith391/didot
Discord tag of Creator: Zen1th#3854
- 3D zig game engine, multi-threaded and modular.
- It even has an editor! https://github.com/zenith391/didot-editor

https://github.com/jack-ji/zplay
Discord tag of Creator: jackji#4456
- 2D simple zig framework intended for game/tool creation
- currently runs on zig 0.9* main branch

https://github.com/danielabbott/Zig-Game-Engine
- Made in Zig 0.6
- 3D OpenGL forward renderer.

https://github.com/fubark/cosmic
Discord tag of creator: fubar#8568
- Single tool that lets you build javascript/TS apps for UI or games
- HOWEVER, it also has a **custom zig graphics library** as one of its dependencies
- https://github.com/fubark/cosmic/tree/master/graphics
  - Pretty far along, can even read svg files

https://github.com/bootradev/cupcake
Discord tag of creator: bootra#1648
- an app framework for making small and delicious games! (very wip)
- WEB FIRST
- meant for doodling around with game development in zig
- uses WebGPU

https://github.com/gamercade-io/zig-template
Discord tag of creator: TheRealZerve#1134
- Zig bindings for gamercade
- gamercade is "The ultimate WASM powered fantasy console and platform"
- focused on easy implementation of multiplayer for developers, and pushing the boundaries of a fantasy console to its limits

## Zig Game UI

https://github.com/JonSnowbd/ZT
Discord Tag of creator: Aetherwind#8836
- A zig-contained library for Windows and Ubuntu that automatically compiles and links ImGui, OpenGL, stb_image, and GLFW into typed packages.
- ZT will always target the latest dev version of Zig, and will create a branch for stable releases when convenient.
- More of a UI thing than gamedev, but seems related 

## Zig Game Dev Adjacent Libraries
https://github.com/prime31/zig-ecs
- zig rewrite of the popular ECS library Entt.

https://github.com/kooparse/zalgebra
- Linear algebra library for games and computer graphics.

https://github.com/kooparse/zgltf
- A glTF 2.0 parser written in Zig, aiming to replace the use of some C/C++ libraries.

## Zig Bindings to existing game engines
https://github.com/linuxy/godot-zig
- zig bindings for Godot 3.4

## Zig Game Physics
https://github.com/silversquirl/phyz
Discord Tag of creator: squirl#0047
- 2D game physics engine, still alpha quality

## Zig Ports of C Libraries

https://github.com/Guigui220D/zig-sfml-wrapper
- Zig wrapper for the SFML library

https://github.com/MasterQ32/SDL.zig
- Zig package that provides you with the means to link SDL2 to your project

https://github.com/Snektron/vulkan-zig
- Vulkan bindings for Zig

https://github.com/SpexGuy/Zig-Oculus-Quest
- Oculus Quest and Quest 2 bindings for Zig

https://github.com/hexops/mach-glfw
- Ziggified GLFW bindings

https://github.com/Not-Nik/raylib-zig
- Manually tweaked, auto generated raylib bindings for zig.
- Bindings tested on raylib version 3.7 and Zig 0.9.0-dev
- Currently only supports a subset of raylib.

## Zig Game Art Tools

https://github.com/fabioarnold/MiniPixel
- tiny pixel art editor made in zig

## Zig Game Dev Tutorials
https://dev.to/fabioarnold/setup-zig-for-gamedev-2bmf
- a step by step guide on how to get started with game development using the Zig programming language on Windows


