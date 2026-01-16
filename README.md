# World Domination 3D

*World Domination 3D* is a high‑octane, browser‑based 3D survival shooter built with **Three.js** and **Tailwind CSS**. Defend your city against endless waves of enemies, recruit an army, and rank up to unlock devastating weaponry.

## 🎮 Gameplay Overview

In **World Domination 3D** you take command of a lone soldier defending a sprawling urban landscape. As you eliminate hostiles, you gain experience and recruits, eventually evolving into a powerful General capable of calling in nuclear strikes.

### Core Mechanics

- **Progression System:** Start as a Soldier and rank up at specific kill milestones (10, 25, 50).  
- **Squad Command:** Every 10 kills grants you an automated AI ally that joins your formation and assists in combat.  
- **Dynamic Difficulty:** Enemies spawn more frequently and include heavier units (Tanks) as you progress.  
- **Visual Themes:** Toggle between High‑Contrast Dark Mode and Clean Light Mode in real‑time.

## 🕹️ Controls

| Action         | Control                           |
|---------------|-----------------------------------|
| Move Forward   | **W**                             |
| Move Backward  | **S**                             |
| Rotate Left    | **A**                             |
| Rotate Right   | **D**                             |
| Fire Weapon    | **Left Click** (auto‑aims to nearest target) |
| Pause Game     | **P** or UI Button               |
| Toggle Theme   | UI Sun/Moon Button               |

## 🚀 Ranking & Upgrades

| Rank    | Kills Required | Weapon         | Specialty                         |
|---------|---------------:|---------------|-----------------------------------|
| Soldier | 0              | Rifle         | Standard infantry unit.            |
| Tank    | 10             | Heavy Cannon  | High damage, slower movement.      |
| Pilot   | 25             | Dual Missiles | Elevated flight and rapid‑fire projectiles. |
| General | 50             | Plasma Beam   | Devastating damage + **Nuke Inbound** event. |

## 🛠️ Technical Details

- **Engine:** Three.js (WebGL)  
- **Styling:** Tailwind CSS  
- **Audio:** Web Audio API (procedurally generated sound effects)  
- **Architecture:** Single‑file HTML/JavaScript application

### Key Features

- **Procedural City:** Buildings are generated with random heights and colours every session.  
- **Smart UI:** Features a glassmorphism top bar with real‑time health, XP progress and kill tracking.  
- **Combat AI:** Enemies use basic pathfinding to pursue the player and auto‑fire when within range.  
- **Visual Feedback:** Crosshair locking mechanism and red‑flash damage overlay.

## 📦 Installation & Running

Because this is a single‑file web application, no installation is required:

1. Save the code as `game.html`.  
2. Open **game.html** in any modern web browser (Chrome, Firefox or Edge recommended).  
3. Ensure you have an active internet connection to load the Three.js and Tailwind CSS CDNs.

Developed as a high‑performance 3D web demonstration.
