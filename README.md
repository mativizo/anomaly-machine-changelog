# anomaly-machine-changelog

## Dev progress:
![Current Version](https://img.shields.io/badge/Current_version-0.1.2_alpha-blue)
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
- [0.1.1-alpha](#011-alpha)
- [0.1.0-alpha](#010-alpha)

### Upcoming
*State: Work in progress*
*Started: 11/11/26*
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
  - AMbient bus effects
- Lights model - bulb emission material reflects the state

> SOON.




## BACKLOG:
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
