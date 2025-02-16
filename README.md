# vkEngine
![vkEngine screen shot](https://github.com/seishuku/vkEngine/blob/master/screen%20shot.png)

vkEngine, my long term "game engine" project.
Might end up as an actual game at some point, no idea when.

This started long long ago in 2004, with OpenGL and ATI GPU demos... My only game that has actually used this "engine" was my [Tetris game/graphics demo](https://github.com/seishuku/Tetris).

I also have the [OpenGL version](https://github.com/seishuku/Engine), this is a *far* more evolved codebase than that though, the OpenGL version I should archive the repo as I haven't touched it in quite some time.

To-do (in no particular order):
- Replace audio code with Soloud library
- Switch to Jolt Physics System for Physics
- Streamline post processing effects (it's kind of tacked on right now)
- Improve networking (this *kind of* works, but physics system is a problem, [server here](https://github.com/seishuku/vkEngineServer))
- Integrate support for GLTF 2.0 for 3D model animation, blendshapes, bones, inverse kinematics and so forth.
- Improve UI and Enable Drawings
- Abstract Vulkan API more
- Remove game code from Engine.c code
- Fix Font Rendering - Glyph Caching, Reduce Shader Code for Fonts, and etc
- Profit?


External dependencies for building this (versions as of this writing, newer *should* work):
 - libvorbis 1.3.7
 - libogg 1.3.5
 - OpenXR 1.2
 - portaudio 2.0
 - Vulkan 1.3.231.1
 - cgltf 1.15
 - soloud Aug 12, 2024, Commit #e82fd32
 - HandmadeMath May 28, 2024, Commit #bdc7dd2
 
(note: cmake should automatically fetch these dependencites)
