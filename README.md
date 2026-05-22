# Cowboy Aim Trainer

A fast-paced western-themed aim trainer made in Unity for a school project. The game combines quick reaction shooting mechanics with arcade-style gameplay inspired by aim trainers like Aimlabs.

## Overview

Cowboy Aim Trainer is a first-person shooting game where the player must quickly eliminate moving targets while improving accuracy, reaction time, and precision. The game focuses on simple but satisfying gameplay mechanics with a western/cowboy atmosphere.

The project was created using the Unity Engine and C# scripting.

---

# Features

- First-person shooting mechanics
- Mouse-controlled aiming system
- Raycast weapon system
- Animated recoil effect
- Sound effects for shooting
- Random target spawning
- Score and timer system
- Pause menu
- Target movement system
- Increasing challenge through moving targets
- Western / cowboy-inspired gameplay style

---

# Technologies Used

- **Game Engine:** Unity
- **Programming Language:** C#
- **Input System:** Unity Input System
- **Physics:** Unity Rigidbody & Raycasting
- **Audio:** Unity AudioSource
- **Version Control:** Git & GitHub

---

# Gameplay

The player enters a training arena where targets appear around the map. Using a revolver-style weapon, the player must shoot as many targets as possible before the timer runs out.

Smaller targets move faster and are harder to hit, while larger targets are slower and easier to track. The game rewards fast reactions and accuracy.

---

# Controls

| Action | Control |
|---|---|
| Move | WASD |
| Look Around | Mouse |
| Shoot | Left Mouse Button |
| Pause | ESC |

---

# Scripts Overview

## Gun.cs
Handles the weapon shooting system using raycasting.

### Responsibilities:
- Detects player shooting input
- Fires raycasts
- Detects hit targets
- Applies hit logic
- Communicates with score and timer systems

---

## AnimationRecoil.cs
Creates the recoil animation effect for the weapon.

### Responsibilities:
- Moves weapon backward during shooting
- Returns weapon to original position
- Plays shooting sound effects

---

## PauseManager.cs
Controls pausing and resuming gameplay.

### Responsibilities:
- Opens pause menu
- Stops game time
- Resumes gameplay

---

## GameTimer.cs
Handles match timing and game-over conditions.

### Responsibilities:
- Tracks remaining time
- Ends game when timer reaches zero
- Displays timer UI

---

## Target Movement Scripts
Controls movement behavior for spawned targets.

### Responsibilities:
- Random movement
- Speed scaling based on target size
- Collision handling

---

# Development Challenges

During development, several technical challenges were solved:

- Implementing Unity's new Input System
- Synchronizing recoil animation with shooting
- Managing object spawning and movement
- Preventing null reference errors in UI systems
- Balancing gameplay difficulty
- Optimizing target spawning performance

---

# What I Learned

This project helped improve skills in:

- Unity game development
- C# scripting
- Game logic design
- Debugging and fixing errors
- Player input systems
- Audio integration
- Physics and raycasting
- UI management
- GitHub project organization

---

# Future Improvements

Possible future updates include:

- Multiple weapons
- Combo scoring system
- Leaderboards
- More maps
- Difficulty settings
- Better animations
- Enemy AI
- Multiplayer mode
- Visual effects improvements
- Save system

---

# Installation

## Requirements

- Unity 2022 or newer
- Windows PC

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/yourrepository.git
```

2. Open the project in Unity Hub
3. Load the main scene
4. Press Play inside the Unity Editor

---

# Project Structure

```text
Assets/
├── Scripts/
├── Audio/
├── Prefabs/
├── Materials/
├── Scenes/
├── UI/
└── Animations/
```

---

# Credits

Developed as a school project using Unity Engine.

Tools and technologies used:
- Unity
- Visual Studio
- GitHub

---

# Screenshots

Add gameplay screenshots here.

---

# License

This project is for educational purposes.

