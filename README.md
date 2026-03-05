# Unseen Anomaly 🚪👁️

**A short, psychological first-person thriller created for Godot Wild Jam #82 (Theme: Unseen).**

Navigate a looping, liminal office hallway. Your goal is simple: observe your surroundings carefully. If the hallway is exactly as you remember it, proceed forward. If you spot anything out of the ordinary—an _unseen anomaly_—turn back. Make 8 correct choices to escape. Make a mistake, and you are sent back to floor 0.

## 🎮 How to Play

- **Observe:** Memorize the layout, objects, and sounds of "Floor 0".
- **No Anomaly:** If the hallway is normal, walk through the **Forward** door.
- **Anomaly Found:** If you notice _anything_ weird (missing objects, strange noises, paranormal events), walk through the **Backward** door.
- **Goal:** Reach Floor 8 to escape.

## ⌨️ Controls

- **WASD / Arrows:** Move
- **Mouse:** Look around
- **Escape:** Free mouse cursor

## 🛠️ Built With

- **Engine:** Godot Engine 4.6 (GL Compatibility)
- **Controller:** Modified [ProtoController by Brackeys](https://github.com/Brackeys/brackeys-proto-controller) (CC0)
- **Assets:** Various 3D models (Lockers, Chairs, Doors, Ceiling Lights) and audio cues tailored for a tense atmosphere.

## 📂 Project Structure

- `scenes/`: Contains the main game loop, the normal hallway, the win screen, and all the anomaly variations (e.g., `lights_out_hallway.tscn`, `thrown_chair_hallway.tscn`).
- `scripts/`: Contains the core logic.
- `game_manager.gd`: The AutoLoad singleton that manages the looping logic, win state, and randomizes anomalies (60% chance to spawn after Floor 0).
- Trigger-specific scripts for dynamic anomalies (e.g., throwing the chair, turning off the lights).

- `assets/`: 3D models, textures, and sound effects.

## 🚀 How to Run

1. Clone or download this repository.
2. Open the Godot Engine (v4.6 or newer recommended).
3. Import the project using the `project.godot` file.
4. Open `scenes/Main.tscn` and hit Play!
