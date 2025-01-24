# Cub3D - RayCasting Project

Hello, this project is part of the **Ecole42 Software School** curriculum, designed to create a **3D game simulator** that allows movement within a **maze** using fundamental **raycasting** principles. The game is developed in **C programming language** using the **MiniLibX** library and operates by reading **.cub** files containing a simple map structure.

---

## 📌 Project Features

- **Rendering with Raycasting**: The player can navigate a **3D environment** within the maze.
- **Wall Textures**: Walls are covered with **different textures** based on their facing direction (**North, South, East, West**).
- **Floor and Ceiling Colors**: The floor and ceiling can be assigned **independent colors**.
- **Dynamic Controls**:
  - Move using **W, A, S, D** keys.
  - Change view direction with **Left and Right arrow** keys.
  - Press **ESC** to exit the game.
  - Click on the **red cross** on the window to close it.
- **Map Structure**: The map is read from **.cub** files and supports the following characters:
  - `1` : **Walls**
  - `0` : **Empty spaces**
  - `N, S, E, W` : **Player's starting position and orientation** (**North, South, East, West**)

---

## 🚀 Installation & Execution

To run the project, follow these steps:

```bash
git clone https://github.com/yourusername/cub3D.git
cd cub3D
make
./cub3D map.cub
```

---

## 🎮 Controls

| Key | Action          |
| --- | --------------- |
| W   | Move forward    |
| A   | Move left       |
| S   | Move backward   |
| D   | Move right      |
| ← → | Look left/right |
| ESC | Exit the game   |

---

## 📁 File Structure

- `cub3D.c` → Main program file
- `raycasting.c` → Ray-casting algorithm implementation
- `parsing.c` → Map file parsing logic
- `textures/` → Folder containing wall and floor textures
- `Makefile` → Compilation rules

---

## 🎯 Mandatory Features

- Display a **3D first-person view of a maze** using **MiniLibX**.
- Support **different wall textures** for different directions (**North, South, East, West**).
- Allow **customizable floor and ceiling colors**.
- Read map data from a **.cub** file.

---

## 🎁 Bonus Features
**Note:** THERE IS NO BONUS PART IN THIS PROJECT
- **Wall collisions**
- **Minimap system**
- **Doors that can open and close**
- **Animated sprites**
- **Mouse-controlled view rotation**

---

### 🎖️ Special Thanks

I sincerely thank my teammate **ydunay** for their valuable contributions during the development of this project. Without their support and collaboration, this project would not have been completed. 🙌

