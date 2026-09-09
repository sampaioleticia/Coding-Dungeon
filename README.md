# Coding Dungeon

A text-based educational game in Python where the player advances through a dungeon, facing monsters and traps by solving programming logic problems. Instead of simple combat commands, progress depends on correctly answering coding challenges (swapping variables, reversing a list, checking palindromes, summing elements, finding the maximum value, among others).

## How It Works

- The player moves through the dungeon (`hero.moveRight()` / `hero.moveLeft()`), generated with randomly placed monsters and traps.
- Encountering a monster or falling into a trap triggers a programming problem. Answering correctly deals damage to the enemy (or reduces incoming damage), while a wrong answer penalizes the character.
- At the end of the path, a special monster tests the player one last time before completing the dungeon.
- The character accumulates health, strength, defense, and XP throughout the journey.

## Project Structure

- `dungeon.py`: dungeon logic (monster/trap generation, programming problem bank, movement, and combat resolution)
- `personagem.py`: character class (attributes, damage, rewards)
- `usuario.py`: user/player management
- `test_dungeon_e_personagem.py` and `test_usuario.py`: unit tests for the main classes
- `UML.png`: UML diagram of the project
- `Coding Dungeon.pdf`: project documentation/report

## Tech Stack

- Python
- Unit testing (unittest)
- Object-oriented modeling (documented via UML diagram)

## Purpose

Project developed to reinforce programming logic and data structure concepts in Python through gamification, combining object-oriented programming with an interactive text-based game layer.
