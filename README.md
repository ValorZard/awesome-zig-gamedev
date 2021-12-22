# List of Zig Gamedev Projects

## Open Source Zig Games
https://github.com/holobeat/zig-wasm-snake
- The game of snake implemented in zig and running on webassembly.

https://github.com/fabioarnold/zig-gorillas
- 2-player local multiplayer game. Take turns throwing an exploding banana at each other.

https://github.com/thejoshwolfe/legend-of-swarkland
- Nethack inspired 2D Simple turn-based action fantasy puzzle sandbox.
- rougelike

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


Stephen Gutekanst (@slimsag#2321 on Discord) has been building an engine
website: https://hexops.com/mach
twitter: <https://twitter.com/slimsag>
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

## Zig Game UI

https://github.com/JonSnowbd/ZT
Discord Tag of creator: Aetherwind#8836
- A zig-contained library for Windows and Ubuntu that automatically compiles and links ImGui, OpenGL, stb_image, and GLFW into typed packages.
- ZT will always target the latest dev version of Zig, and will create a branch for stable releases when convenient.
- More of a UI thing than gamedev, but seems related 

## Zig Game Dev Adjacent Libraries
https://github.com/prime31/zig-ecs
- zig rewrite of the popular ECS library Entt.

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

## Zig Game Art Tools

https://github.com/fabioarnold/MiniPixel
- tiny pixel art editor made in zig

## Zig Game Dev Tutorials
https://dev.to/fabioarnold/setup-zig-for-gamedev-2bmf
- a step by step guide on how to get started with game development using the Zig programming language on Windows


