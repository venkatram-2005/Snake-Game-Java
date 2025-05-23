# Snake Game in Java

## Overview
This is a classic **Snake Game** built using **Java** and the **Swing** library for creating the graphical user interface (GUI). The game allows the player to control a snake that eats apples to grow longer. The objective is to eat as many apples as possible without colliding with the snake's body or the boundaries. The game also features a **wrap-around** mechanic, where the snake can pass through walls and appear on the opposite side.

## Features
- Classic snake game mechanics (move, eat, grow).
- **Randomly spawned apples** that increase the snake's length when eaten.
- **Wrap-around walls**, allowing the snake to continue from the opposite side when it hits the boundary.
- **Game Over screen** showing the player's score when the snake collides with its own body.
- **Score display** that updates each time the player eats an apple.

## Snippets: (You can also check out the video)

![image](https://github.com/user-attachments/assets/97283098-5fe4-4fb6-bf92-d0300a906bcb)

![image](https://github.com/user-attachments/assets/456d746a-0e56-48b5-a3c5-2eb71ddb3e0e)

## How to Run

### Prerequisites
- **Java 8 or higher**: This game is built using the Java programming language with the Swing library, which is bundled with the JDK.
- A working **IDE** (like IntelliJ IDEA, Eclipse, or NetBeans) or a **command-line setup**.

### Steps to Run
1. **Clone the repository** (or copy the Java file):
    ```bash
    git clone <your-repo-url>
    ```

2. **Open the project in an IDE**:
    - If you're using an IDE like **IntelliJ IDEA** or **Eclipse**, simply open the `.java` file (`GamePanel.java`).

3. **Compile and Run**:
    - If using an IDE, press the "Run" button to execute the program.
    - If using the command line:
        1. Navigate to the directory where the `GamePanel.java` file is saved.
        2. Compile the Java file:
            ```bash
            javac GamePanel.java
            ```
        3. Run the compiled program:
            ```bash
            java GamePanel
            ```

4. **Enjoy the Game**:
    - The game window will pop up. Use the **Arrow Keys** (`UP`, `DOWN`, `LEFT`, `RIGHT`) to control the snake.
    - Eat the apples to grow the snake and score points.
    - Avoid colliding with your own body or the walls (you can wrap around the walls if you hit the edges).

## Controls
- **Arrow Keys**: Control the snake's direction (`UP`, `DOWN`, `LEFT`, `RIGHT`).

## Game Mechanics
- The snake initially has 6 body parts and moves in the right direction.
- Each time the snake eats an apple, it grows by one unit and the score increases.
- If the snake hits its own body, the game ends, and the **Game Over** screen appears with the final score.
- The snake can pass through the edges of the screen and come out on the opposite side (wrap-around feature).

## Customization
You can customize the following aspects of the game by modifying the code:
- **Screen size**: Change `SCREEN_WIDTH` and `SCREEN_HEIGHT` to resize the game area.
- **Snake speed**: Adjust the `DELAY` variable to change how fast the snake moves.
- **Snake color**: Modify the color in the `draw()` method to change the snake's appearance.
- **Apple color**: Modify the apple's color in the `draw()` method.

