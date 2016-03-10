# Multiple Lighting Tutorial

This program serves to demonstrate the concept of multiple lighting.

# About

Combines the Directional Light, Point Light, and Spot Light projects together to allow several lights to be placed in a scene at once. This introduces using a uniform struct array of lights and a uniform integer that defines the number of lights. Directional lights are identified as the position variable w = 0. Point lights are differentiated from spotlights by setting the cone angle to 180 or higher. Realistically, this should be done with Uniform Buffers.

# Setup

In order to setup, run the following in a shell, then open the project in your preferred editor. Windows setup has been configured for use with Visual Studio.

Windows:
```
cd path/to/folder
setup.cmd
```
Linux:
```
cd path/to/folder
./setup
```

# Credits

For more reading, check out [this tutorial on lighting](http://www.tomdalling.com/blog/modern-opengl/08-even-more-lighting-directional-lights-spotlights-multiple-lights/)
