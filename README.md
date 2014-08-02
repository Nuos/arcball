Arcball Rotation Control
========================
Allows the user to interact with the orientation of an object. The user can
orient the object freely by dragging in any direction on the arcball, or by
dragging along a constraint axis.

+ Press `F1` to toggle helpers.
+ Hold `CTRL` to show body constraint axes.
+ Hold `SHIFT` to show camera constraint axes.
+ Hold `CTRL` and `SHIFT` to show world constraint axes.

License
-------
Licensed under GNU GPL v3.0.

How-to
------
You will need a C++11 compiler, GLM, GLEW and SDL2. Consult SConstruct for
details.

Build and run

    $ scons
    $ cd bin
    $ ./arcball

Cleanup

    $ scons -c

References
----------
1. Ken Shoemake. ARCBALL: A User Interface for Specifying Three-Dimensional Orientation Using a Mouse. Graphics interface '92, pages 151-156, 1992.
2. Ken Shoemake. Graphics Gems IV, chapter Arcball Rotation Control. Academic Press Inc, 1994.
