# 3D Maze Game

## Introduction

Welcome to the 3D Maze Game project! This game was developed using raycasting to create a 3D perspective from a 2D map. It was built with SDL2 and written in C, aimed at providing an immersive experience for users navigating through a maze.

- **Author's LinkedIn**: [https://www.linkedin.com/posts/ahmed-sayed-salih-0440a128a_my-3d-maze-game-project-introduction-the-activity-7221930504181174272-dKIX?utm_source=share&utm_medium=member_desktop](#)

## Installation

To install and run the project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/ahmedsayed940/The_maze.git
    cd 3d-maze-game
    ```

2. **Install SDL2:**

    Follow the instructions in the [SDL2 documentation](https://wiki.libsdl.org/Installation) to install SDL2 on your system.

3. **Compile the project:**

    ```bash
    gcc -Wall -Werror -Wextra -pedantic -o maze main.c -lSDL2
    ```

4. **Run the game:**

    ```bash
    ./maze
    ```

## Usage

Once the game is running, you can control the player (camera) using the following keys:

- `W`: Move forward
- `S`: Move backward
- `A`: Move left
- `D`: Move right
- `Left Arrow`: Rotate camera left
- `Right Arrow`: Rotate camera right

Navigate through the maze, avoid walls, and try to reach the endpoint!

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Open a pull request

Please ensure your code adheres to the project's coding standards and includes appropriate comments.

## Related Projects

Here are some related projects that might interest you:

- [Raycasting Tutorial](https://lodev.org/cgtutor/raycasting.html)
- [SDL2 Documentation](https://wiki.libsdl.org/FrontPage)
- [Wolfenstein 3D](https://github.com/id-Software/wolf3d)

## Licensing


---

Thank you for checking out the 3D Maze Game project!

