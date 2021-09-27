This is the release version of BuildEngine v1.1.

BuildEngine is a private project of mine. It's a lightweight java game engine. This
version of the engine uses the build in java graphics library (AWT) for rendering.
Features:
 - Java rendering using an custom advanced Draw class, handling resizing, unit scaling and rotation.
 - Audio like sound effects and music handling.
 - Configuration file I/O, for easy writing and retrieving data.
 - A collection of core abstract classes based on ECS, capable of creating any game (see core-architecture).
 - An advanced collision system, using SAT. Also a basic physics implementation. Both are customizable.
 - Supports animations, custom rendering, but also an elaborate implementation for default rendering.
 - The input system is capable of detecting press, hold and release for key and mouse plus many more features.
 - A small math library, containing full Vector2 clases, shapes and transforms used for the collision system.
 - Static event scheduler, so you can start timed or repeating events anywere.
 - Asset handling, like reading and saving in chache.
 - Easy and fun to program in :)

Check the example folder to get confortable with the engine's structure and capabilities.


INSTALLATION

The JAR file contains the whole library, including some test and example classes.
Add this JAR file to your java project (using your IDE, or gradle). Now you can use
the library to create your games.
