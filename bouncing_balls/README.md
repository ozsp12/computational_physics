# Bouncing Balls

This module implements two-dimensional particle motion inside a square domain with idealized elastic reflection at fixed boundaries. It is a compact example of discrete time stepping, collision rules, real-time visualization, and state updates with Pygame.

## Material and execution

The notebook `bouncing_balls.ipynb` contains the model and implementation. It opens an interactive graphical window and therefore requires a local display; closing the window terminates the simulation.

The boundary rule is an idealization. The example does not model finite collision duration, deformation, friction, rotation, ball–ball collisions, or accumulated integration error. Those effects must be introduced explicitly before interpreting the program as a material collision model.

[Return to the repository contents](../CONTENTS.md).
