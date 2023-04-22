# Engine3D
This is a 3D graphics engine (still a work in progress) built on top of the olcConsoleGameEngine. Currently, it includes:
* A 3D modeling system based on triangle meshes
* A matrix manipulation system for moving 3D models about in 3D space (translation, rotation, etc.)
* A system for projecting 3D models onto a 2D screen, taking the field of view, aspect ratio, z-displacement into account (simulating human vision)
* Triangle culling (by way of camera and surface normal interaction and depth testing)
* A primitive lighting system
