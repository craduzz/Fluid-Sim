# Fluid-Sim
 Partial Proyect of fluid sim


## Instrucctions: 
** To add a density write `DENSITY:` then the coordinates in the following format:

`a b c d`

where:

`a` < `b` and `d` < `c`

`a` & `b` are y-coordinate of the density box

`d` % `c` are x-coordinate of the density box

Write `END` when done writing the coordinates


** To add objects to the simulation write `OBJECTS:` then the coordinates in the same format for `DENSITY:`:

`a b c d`

Write `END` when done writing the coordinates


** To add velocity vectors write `VECTORS:` then the coordinate in the following format:

`a b`

where: 

`a` is the y-coordinate of the origin of the vector force

`b` is the x-coordinate of the origin of the vector force

Write `END` when done writing the coordinates

** To change the color map write `SET_COLOR: ` then the name of the color map to use. Example: `SET_COLOR: hot`

Here is a link where to find the available [color maps](https://matplotlib.org/stable/tutorials/colors/colormaps.html)

** To set the type of vector animation write `VECTOR_ANIMATION: ` then the name of the animation type.

Currently there are only 2 animation types: `rotate` and `spray`

**A vector animation is required for the simulation to work**
