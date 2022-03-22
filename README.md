# Computer_Graphics
## Description
The object of the project is the implementation of a third-person navigation game within an open
synthetic environment full of obstacles. The player (a virtual plane) moves at a constant speed within a
clogged perimetrically environment, following a series of buoys, which it consumes
getting points when you pass close enough to them. Any conflict with the constants or possibly
moving objects can be fatal and prematurely end our exploration. The terrain is
closed from all sides except above, but the boat should not leave above the maximum height
of the model of the soil.

## The Ιmplementations
In our project, we managed to implement in code the following functions:
- Loading the terrain (terrain.obj) and the plane (craft.obj).
- Use of the provided albedo (base color), normal mask maps (see next section).
- Create code for navigating the plane freely within the terrain.
- Creation of a camera that we are moving.
- Application of at least one light source (sun) with shadow map type shadows or as a parallel,
distant source as either as a spotlight (orthographic/perspective shadow map projection).
- Use of a Physically correct model, for the shading in the fragment shader, such as normalized
Blinn-Phong or Cook-Torrance.
- Detection of collisions between vessel and terrain (it is coming soon).

## The Structure Of The Repository
### Our repository is organized as follows:
- **3rd party**: OpenGL and C++ libraries 
- **Assets**: here is the skin, object and shaders of every object (terrain and craft) 
- **Source**: C++ code that implements the functions
- **screenshots**: Οur journey through experiments
### We also have three branches:
- **main**: the final code that works successfully
- **ideas**: are the experiments on arithmetic operations that we were thinking of doing in order to have more qualitative shadows 
- **second_thoughts**: the branch where we dealt fully with the collision

## Team Members
- [Achilleas Aimilios Matthes](https://github.com/AchillMt)
- [Michalis Ikonomou (Michail Isidoros Oikonomou)](https://github.com/mikonomou)
- [Despoina Papadopoulou](https://github.com/Despoina2000)
