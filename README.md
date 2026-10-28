# 3D Cube Transformations — BSIT411

A Python graphics project developed using **Pygame Community Edition** and **PyOpenGL**, demonstrating fundamental 3D geometric transformations through an interactive, animated object consisting of five connected cubes.

## Features

- Five connected cubes with pink, red, blue, orange, and green colors.
- Continuous 3D rotation along the X, Y, and Z axes.
- Keyboard-controlled movement and scaling.
- Pause, resume, and reset functionality.
- Perspective projection and depth testing.
- Real-time animation targeting 60 FPS.

## Technologies Used

- Python 3.14
- Pygame Community Edition (`pygame-ce`)
- PyOpenGL
- Visual Studio Code

## Installation

Install the required Python libraries:

```powershell
python -m pip install pygame-ce PyOpenGL
```

## How to Run

1. Open the project in Visual Studio Code.
2. Select the correct Python interpreter.
3. Open the main Python file.
4. Select **Run Python File in Terminal**, or execute:

```powershell
python Maxilom_BSIT411_05PT1.py
```

Replace the filename if your Python file has a different name.

## Keyboard Controls

| Key | Function |
|---|---|
| Left / Right Arrow | Move horizontally |
| Up / Down Arrow | Move vertically |
| Q | Decrease object size |
| E | Increase object size |
| Space | Pause or resume rotation |
| R | Reset transformations |
| Esc | Exit |

## Geometric Transformations

**1. Translation — `glTranslatef()`**

Allows the cubes to be positioned in a connected arrangement and enables the entire object to move horizontally and vertically.

**2. Rotation — `glRotatef()`**

Applies continuous rotation along the three coordinate axes to demonstrate three-dimensional movement.

**3. Scaling — `glScalef()`**

Controls the size of individual cubes and allows users to enlarge or shrink the complete object.

## Troubleshooting

If VS Code displays `Import "pygame.locals" could not be resolved`, select the Python interpreter containing `pygame-ce` and reload the VS Code window.

Verify the dependencies using:

```powershell
python -c "import pygame; import pygame.locals; import OpenGL; print('Imports successful!')"
```

## Project Information

**Course:** BSIT411  
**Project:** 3D Cube Transformations  
**Developer:** Arcadio Mushi P. Maxilom

This project demonstrates the practical application of geometric transformations, basic 3D rendering, and interactive graphics programming using Python and OpenGL.