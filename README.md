# Pong++

Pong++ is a text-based C++ implementation of the classic Pong game. The project is structured using multiple source and header files, with separate components for the game engine, sprite handling, and project setup. It was built to practice object-oriented design, game loop structure, and basic 2D game development concepts in C++.

## Features

- Classic Pong-style gameplay
- Modular C++ project structure
- Sprite-based game objects
- Separate game engine and gameplay logic
- Asset folder for project resources
- Visual Studio project support

## Project Structure

- `Source.cpp`  
  Main entry point of the game. Starts the application and connects the core game flow.

- `GameEngine.h` / `GameEngine.cpp`  
  Contains the main game engine logic, such as initialization, update loop, rendering flow, and overall game control.

- `Sprite.h` / `Sprite.cpp`  
  Defines and implements sprite-related behavior for handling game objects on screen.

- `Assets/`  
  Stores game assets and supporting resource files used by the project.

- `ThePongGameW2022.sln`  
  Visual Studio solution file used to open the full project in Visual Studio.

- `ThePongGameW2022.vcxproj`  
  Visual Studio C++ project file containing build settings and project configuration.

- `ThePongGameW2022.vcxproj.filters`  
  Visual Studio filters file used to organize files into folders in the IDE.

- `packages.config`  
  Stores package dependency information for the Visual Studio project.

- `.gitignore`  
  Specifies files and folders Git should ignore.

- `.gitattributes`  
  Defines Git attribute settings for the repository.

- `.DS_Store`  
  macOS system file; not part of the actual game logic.

## Tech Stack

- **Language:** C++
- **IDE/Platform:** Visual Studio
- **Concepts Used:** Object-oriented programming, game loop, modular design, sprite handling

## How to Run

1. Open `ThePongGameW2022.sln` in Visual Studio.
2. Build the project.
3. Run the game from Visual Studio.

## Learning Goals

This project helped practice:
- C++ class design
- File-based project organization
- Game engine structure
- Basic rendering and object handling
- Managing a multi-file Visual Studio project

## Notes

This repository includes both source code and Visual Studio project files, making it easy to open and run directly in a Windows development environment.
