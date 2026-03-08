# Maze Chase Game (C)

A simple console-based maze game written in C.  
The player controls a thief trying to escape from a police officer inside a maze.  
The goal is to reach the escape point before getting caught.

## Gameplay

- The player controls the **Thief (T)**.
- The computer controls the **Police (P)**.
- The escape point is shown as **>**.
- Walls (**W**) block movement.
- The thief must reach the escape point without getting caught by the police.

## Controls

| Key | Action |
|----|----|
| W | Move Up |
| S | Move Down |
| A | Move Left |
| D | Move Right |

## Difficulty Levels

### Easy
- Police moves randomly among possible positions.

### Hard
- Police uses **Manhattan Distance** to move toward the thief.
- It tries to choose the shortest path and avoids unnecessary backtracking.

## Game Features

- 16x16 maze grid
- Random spawning positions
- AI-based police movement
- Two difficulty levels
- Escape objective system
- Replay option

## Game Symbols

| Symbol | Meaning |
|------|------|
| T | Thief (Player) |
| P | Police (Computer) |
| W | Wall |
| > | Escape Point |
| (space) | Empty cell |

## Technologies Used

- C Programming Language
- Standard Libraries:
  - `stdio.h`
  - `stdlib.h`
  - `time.h`
  - `math.h`

## How to Run

1. Compile the code:

```bash
gcc maze_chase.c -o maze
