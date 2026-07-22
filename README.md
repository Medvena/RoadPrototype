# Road Prototype - Unreal Engine 5.7.4

## Overview

This project is a small Unreal Engine 5.7.4 prototype created as part of a technical exercise.

The objective was to create an interactive environment where an element can move. I chose to implement a simple arcade-style car controller driving on a road.

## Features

- Arcade-style vehicle controller
- Forward and reverse movement
- Steering
- Third-person follow camera
- Simple environment using free assets
- Unreal Engine 5.7.4

## Technical Choices

The project uses:

- Unreal Engine 5.7.4
- Blueprint for gameplay logic
- A C++ Pawn base class
- Enhanced Input System

The gameplay logic was intentionally kept simple in order to focus on a clean and understandable implementation.

## Project Structure

```text
Content/
 ├── Blueprints/
 ├── Input/
 ├── Maps/
 └── Environment/
```

## Running the Project

1. Clone the repository.
2. Open `RoadPrototype.uproject` with Unreal Engine **5.7.4**.
3. Launch the project.
4. Press **Play**.

## Controls

| Key | Action |
|------|--------|
| ↑ | Accelerate |
| ↓ | Reverse |
| ← | Turn left |
| → | Turn right |

## Assets

This prototype uses free Unreal Engine assets for the environment and vehicle models.

## AI Usage

OpenAI ChatGPT was used as a development assistant to:
- discuss architecture choices;
- troubleshoot Unreal Engine issues;
- review gameplay logic.

All implementation choices and code were understood and validated before being integrated into the project.