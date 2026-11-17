# anomaly-machine-changelog

## Dev progress:
![Current Version](https://img.shields.io/badge/Current_version-0.2.0_alpha-blue)
![Progress](https://img.shields.io/badge/Progress-13.6%25-orange)
![Release Date](https://img.shields.io/badge/Release-2027-black)
### Sections progress:
![Gameplay](https://img.shields.io/badge/Gameplay-19%25-orange)
![Story](https://img.shields.io/badge/Story-13%25-orange)
![Graphics and Models](https://img.shields.io/badge/Graphics_and_models-23%25-orange)
![Music and Audio](https://img.shields.io/badge/Music_and_audio-7%25-red)
![Tests](https://img.shields.io/badge/Tests-6%25-red)



[Trello Progress Board](https://trello.com/b/5F7r2ZHp/anomaly-machine-blind-fidelity)

## Changelog
- [Upcoming](#upcoming)
- Alpha
  - [0.1.2-alpha](#012-alpha)
  - [0.1.1-alpha](#011-alpha)
  - [0.1.0-alpha](#010-alpha)

### Upcoming
*State: Work in progress*
*Started: 17/11/26*
- Half wall above doors added.
- All interactable elements renamed for map.
- Rewrite the Shader for walls to work seamlessly with half walls.
  - Replaced the wall height, with ceiling and floor world-y.
  - Replaced the other shaders with universal wall shader.
  - Optimization for wall shader.
- Found the map editor bug that breaks the save; backups added.
- Refined the dev targets, to speed up the work progress.
- Reworked the ceiling light model.
- 

> SOON.




## BACKLOG:
### 0.1.2-alpha
*State: Done* | *Date: Nov 17, 2026*
- Door introduced:
  - Door interactions (open/close)
  - Door interactions tweaks (door never opens to the player)
  - Door states (locked / opened / closed)
  - Optimization (130+ FPS on test machine)
- Light switch system rewritten to Events with start sync
- MapEditor:
  - Teleporting
  - Moving elements
  - Cloning elements
  - Removing elements
  - Changing element's properties
  - Connecting logic
- SFX:
  - Door opening / closing / locked
  - Light switch: on / off
  - Player: Steps
  - Ambient Room Tone
- Optimization:
  - Float point optimization (MapEditor only)
- Audio:
  - SFX bus effects
  - Ambient bus effects
- Lights model - bulb emission material reflects the state
- Fixed door state at start
- Fixed ambient sound in house (not attached).
- Light state sync at start.
- Ambient illumination reduced.
- Separated WE for editor and map.

### 0.1.1-alpha
*State: Done* | *Date: Nov 11, 2026*
- Map:
  - Hallway
  - Basement
  - Office
  - Stairs
- Lights and shadows introduction
- Menu:
  - Main menu
  - Game settings (Graphics)
  - Credits screen and trademarks
  - Exit game
- Shaders introduced:
  - Walls
  - Ceilings
  - Floors
- Modular map creation introduced
- Fusebox - fuse - phase - electricity wired
- Game elements:
  - Light switches
  - Tables
  - Bin
  - Fuses
  - Fusebox
- Mechanics:
  - One-slot eq introduced
  - Interaction system - pickup, interact
  - Fixed held item problems
  - Discord Rich Presence introduced
  - Steamworks integration introduced

### 0.1.0-alpha
*State: Done* | *Date: -*
- Game setup
- Player movement
- Test level
- Flashlight
- Electricity System 1.0
- Debug overlay - Electricity Controller)
- Debug overlay - performance metrics
- Fuses introduced
- Fusebox introduced
