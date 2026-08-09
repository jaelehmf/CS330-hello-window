# CS 330 Hello Window

A minimal OpenGL "hello window" project built to verify a working development environment ahead of SNHU's CS 330 (Computational Graphics and Visualization) course.

## Purpose

This project confirms that Visual Studio, GLFW, GLAD, GLEW, and GLM are correctly installed and linked before diving into course material. It opens a window and clears it to a solid background color — the standard first checkpoint in any OpenGL project.

## Tech Stack

- **IDE:** Visual Studio 2026
- **Language:** C++
- **Graphics API:** OpenGL 3.3 (Core Profile)
- **Libraries:**
  - [GLFW](https://www.glfw.org/) — window and input handling
  - [GLAD](https://glad.dav1d.de/) — OpenGL function loader
  - [GLM](https://github.com/g-truc/glm) — math library for vectors/matrices
  - GLEW — included for compatibility, not currently used alongside GLAD

## What It Does

- Opens an 800x600 window titled "Hello Window"
- Clears the screen to a dark teal color each frame
- Closes cleanly when the ESC key is pressed

## Status

✅ Environment verified and building successfully on Visual Studio 2026 (x64/Debug)

## Next Steps

- Draw a basic triangle/mesh using vertex data
- Apply transformation matrices (translate/rotate/scale)
- Build out camera navigation (pitch/yaw controls)
