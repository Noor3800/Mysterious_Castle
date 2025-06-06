# 🏰🐉 MYSTERIOUS CASTLE ADVENTURE - PYTHON TERMINAL GAME 🎮

💫 Can you escape the castle by solving puzzles, unlocking secrets, and finding hidden items?

Welcome to **Mysterious Castle Adventure**, a text-based, terminal-powered Python game where you explore a mysterious castle full of locked doors, cryptic riddles, and magical items. Make your way through secret rooms and grand halls to escape!

---

## 🎮 GAMEPLAY OVERVIEW

🧍 **SINGLE PLAYER MODE**

- Explore rooms like the **Library**, **Dungeon**, **Throne Room**, and **Armory**.
- Pick up and use magical items.
- Solve riddles and logic puzzles to unlock paths.
- Find the secret escape route!

---

## 🌳 HOW IT WORKS

🗺️ **Room-based Navigation**

Each room is a node in a custom map with:

- A detailed description
- Items to collect or examine
- Locked or unlocked directional exits

🧠 **Logic System**

- Binary-style room connections (north, south, east, west)
- Puzzle gates block access until solved
- Inventory-based interaction with locked doors

---

## 🧩 PUZZLES & UNLOCKS

| Area             | Unlock Requirement                  |
|------------------|--------------------------------------|
| 🔐 Secret Room    | Use paper passcode from chest        |
| ⚔️ Armory         | Solve logic puzzle in the dungeon    |
| 👑 Throne Room    | Solve riddle to unlock               |
| 🚪 Escape Tunnel  | Use sword in throne room             |
| 🚪 Grand Hall     | Use the sword key at entrance        |

---

## 📜 HOW TO PLAY

1. **Run the game**
   ```bash
   python adventure_game.py

   ```

2. Use the following commands:

Command	Description
look	View current room description
go [direction]	Move in a direction (north, east, etc.)
take [item]	Pick up an item
drop [item]	Drop an item
use [item]	Use an item to interact with environment
examine [object]	Get more detail about an object
show inventory	View your current items
save	Save your game progress
load	Load previously saved game
help	Show all commands again
quit	Exit the game

  ```
## 💡 EXAMPLE ROOM FLOW

ENTRANCE
 |
 |---> DUNGEON (Solve riddle)
       |
       |---> ARMORY (Get sword)
               |
               |---> THRONE ROOM (Use sword)
                       |
                       |---> ESCAPE TUNNEL 🚪

  ```


💾 FEATURES
🧠 Puzzle-solving gameplay

🧳 Inventory system

🔒 Room unlocking logic

🔁 Infinite replayability

💾 File-based save/load system

🧱 Hidden areas and items


🛠️ TECH STACK

Language: Python

Architecture: Dictionary-based room map

Puzzles: Riddles & logical choices

Save/Load: Plain text file system



🧠 FUTURE IDEAS
🔐 Add file-based memory of player progress

🖼️ Build GUI using Tkinter or Pygame

📜 Add quests, enemies, or NPCs

🔊 Add sound and visual effects

  ```

🚀 RUN THE GAME

git clone https://github.com/your-username/castle-adventure.git
cd castle-adventure
python adventure_game.py

  ```

📝 Answers must be short and case-insensitive where required.


Enjoy the mystery! 🔍🗡️ Escape the castle — if you can...


---
