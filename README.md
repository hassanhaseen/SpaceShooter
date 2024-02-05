# SpaceShooter Game using SFML (C++)

Welcome to the SpaceShooter game implemented in C++ with the SFML library. This 2D game will take you on an interstellar journey filled with space battles and excitement.

## Prerequisites

Before running the game, make sure you have the following installed on your machine:

- SFML library
- G++ Compiler (Mingw-64 for Windows)

## Installation

### Ubuntu/Linux

```bash
sudo apt-get install libsfml-dev
sudo apt-get install build-essential
g++ -c ./main.cpp
g++ main.cpp -o sfml-app -lsfml-graphics -lsfml-audio -lsfml-window -lsfml-system
./sfml-app
