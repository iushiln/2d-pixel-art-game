# Gumball Game

A 2D top-down arcade game built in Godot 4 where you dodge enemies, eat food to score points, and grab power-ups to fight back.

<!-- Optional: add a screenshot or GIF here once you have one
![Gameplay screenshot](path/to/screenshot.png)
-->

## 🎮 Play It

- **Web:** <!-- replace with your itch.io link once published --> (https://iushiln.itch.io/gumball-game)


## 🕹️ How to Play

- **Move:** Arrow keys / WASD
- **Goal:** Eat food to increase your score while avoiding enemies
- **Power-up:** Eating a golden food item lets you shoot enemies for a limited time
- Enemies get faster, spawn more often, and appear in larger groups the longer you survive — there are no fixed levels, just a constant ramp-up in difficulty
- Your best score is saved automatically and shown on the main menu

## ✨ Features

- Continuous difficulty scaling (enemy speed, spawn rate, and spawn size all increase smoothly over time)
- Two enemy types (normal and fast) with different behavior
- Power-up system with a shooting mechanic and looping attack sound
- Persistent high score saved between sessions
- Full sound design: music, UI feedback, and gameplay sound effects
- Game over screen with instant restart

## 🛠️ Built With

- [Godot Engine](https://godotengine.org/) 4.7.1
- GDScript

## 📁 Project Structure

```
├── Scene/              # Scene files (.tscn)
│   ├── game.tscn        # Main gameplay scene
│   ├── main_menu.tscn   # Main menu
│   ├── player.tscn
│   ├── bullet.tscn
│   └── ...
├── Scripts/             # GDScript files (.gd)
│   ├── player.gd
│   ├── EnemySpawner.gd
│   ├── FoodSpawner.gd
│   ├── levelManger.gd   # Score tracking
│   ├── MainMenu.gd
│   ├── GameOverUI.gd
│   ├── Global.gd         # Autoload — persistent high score
│   └── ...
└── assets/
    ├── Music/            # Audio files
    └── ...                # Sprites, fonts, etc.
```


## 🙏 Credits

- Game design & development: Shilan - i did the design
- Sound effects and music: https://pixabay.com/sound-effects/search/game/
