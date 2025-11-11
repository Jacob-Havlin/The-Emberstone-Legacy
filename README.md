# The Emberstone Legacy

## 📜 Concept

"The Emberstone Legacy" is a text-based, turn-based RPG built in Python. Players take on the role of an apprentice at the Silver Spire wizarding academy. When the headmaster, Archmage Valerius, is corrupted by a dark artifact known as the Shadow Ember, it's up to the player to journey through enchanted lands, confront dark forces, and make critical choices to save the academy.

## ✨ Features

* **Character Creation:** Choose from three unique classes (Guardian, Mage, Shadow), each with distinct stats (Strength, Agility, Magic) and a special combat ability.
* **Multi-Stage Story:** Journey from the besieged **Academy** to the mysterious **Whispering Woods** and the dangerous **Crystal Caves** on your quest to find a way to stop the Archmage.
* **Turn-Based Combat:** Engage in tactical, turn-based battles. Choose to **Attack**, **Defend**, use a **Special Move**, or use an **Item**.
* **Randomized Outcomes:** Combat includes dice-roll elements (randomness) for attack damage, critical hits, and dodge chances, making every fight unpredictable.
* **Inventory System:** Collect potions, artifacts, and quest items. Manage your inventory by viewing, using, or discarding items.
* **Branching Choices & Endings:** Your decisions matter! How you resolve conflicts (e.g., fighting vs. diplomacy) will change the story and lead to one of **three distinct endings**.
* **Error Handling:** The game is built to handle invalid commands and edge cases (like an empty inventory or 0 HP) gracefully.

## 🚀 How to Run

### Dependencies

* Python 3.x (No external libraries are required. `random`, `time`, `sys`, and `unittest` are all part of the standard library.)

### Instructions to Play

1.  Save the game code as `game.py`.
2.  Open your terminal or command prompt.
3.  Navigate to the directory where you saved the file.
4.  Run the game using the following command:

    ```bash
    python game.py
    ```

    (or `python3 game.py` on some systems)

### Instructions to Test

This project includes a unit test file to verify the game's core logic.

1.  Ensure both `game.py` and `test_game.py` are in the same directory.
2.  Open your terminal or command prompt.
3.  Navigate to that directory.
4.  Run the test suite using the following command:

    ```bash
    python -m unittest test_game.py
    ```

    (or `python3 -m unittest test_game.py` on some systems)

## 🎮 Basic Commands

* During exploration, you will be given numbered choices (e.g., `1`, `2`, `3`).
* During combat, you can use the following commands:
    * `attack`: Perform a standard physical attack.
    * `special`: Use your class-specific special move (costs MP).
    * `defend`: Halve incoming damage for one turn.
    * `item`: Open your inventory to use an item.
    * `flee`: Attempt to escape combat (not always successful!).
* At any inventory prompt:
    * `use [item name]`: (e.g., `use health potion`)
    * `view [item name]`: (e.g., `view sunstone shard`)
    * `discard [item name]`: (e.g., `discard rusty dagger`)
    * `back`: Return to the previous screen.