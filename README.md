# ClickExplosion
Explosion visualization using D3.js

Simulation can be found at: https://bl.ocks.org/Shaan-B/f7c603d297274cefff0c246cb3d44cc3  
See also: ClickForce, found at https://bl.ocks.org/Shaan-B/852f6b99be4acded0225ae58c7080ce1

This file creates a simulation of dots which can be hit by a explosive force from a mouse click.

Each dot exerts a repulsive force on each other dot, and all dots are attracted to ring using D3's force located in the center of the canvas. Dots are also restricted from moving outside of the canvas area.

Clicking produces a repulsive force at the position of the cursor. Dragging moves the center of the force field, and releasing the click removes the force.

The following parameters can be tweaked:

* numCircles - the number of dots in the simulation
* dropoffRadius - size of click explosion
* explosionTime - number of frames the explosive force is applied (defaults to 1)
* circleRadius - Size of the circle to which the dots are attracted

This simulation is an example of many small objects following simple rules coming together to construct a greater whole, which can itself be considered a single entity (the network of dots).
