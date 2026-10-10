<div align="center">

<img src="OOP2_game%20Testing/src/assets/primordia_banner.png" alt="Primordia Banner" width="100%">

# 🌋 PRIMORDIA 🌊

### *Where the elements clash and only one remains.*

A turn-based elemental battle game written in **Java**.

<br>

![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Game](https://img.shields.io/badge/Genre-Turn--Based_Battle-8A2BE2?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In_Development-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

![Stars](https://img.shields.io/github/stars/jnerlherms/Primordia?style=social)
![Forks](https://img.shields.io/github/forks/jnerlherms/Primordia?style=social)

[🎮 Gameplay](#-gameplay) •
[🧙 Characters](#-playable-characters) •
[📸 Screenshots](#-screenshots) •
[⚙️ Installation](#️-installation) •
[🕹️ How to Play](#️-how-to-play) •
[🤝 Contributing](#-contributing)

</div>

---

## 📖 About The Project

**Primordia** is a Java-based, turn-based fighting game where powerful **elemental champions** face off in strategic duels. Each character wields the power of a different element, with unique skills, strengths, and weaknesses. Choose your fighter, read your opponent, and outsmart them one turn at a time.

> *In the beginning, there were only the elements. Now, they fight for dominance.*

### ✨ Features

- ⚔️ **Turn-based combat** - think before you strike
- 🔥 **Elemental playable characters** - each with their own identity and playstyle
- 💥 **Unique skills & abilities** per character
- 🧠 **Strategy-driven gameplay** - exploit elemental advantages
- ❤️ **Health & energy system** - manage your resources wisely
- ☕ **Built with pure Java** - clean, object-oriented design

---

## 🎮 Gameplay

Battles in Primordia play out in alternating turns. On your turn, you pick an action; then your opponent responds.

```
┌──────────────────────────────────────────────┐
│  PLAYER 1            VS            PLAYER 2  │
┌──────────────────────────────────────────────┐
│  PLAYER 1            VS            PLAYER 2  │
│  🔥 Myrrik                        🌊 Ondine │
│  HP: ██████████ 100       HP: ███████░░░ 70  │
│                                              │
│  [1] Attack   [2] Skill   [3] Defend         │
└──────────────────────────────────────────────┘
```

</div>

### 🔁 Turn Flow

1. 🎯 **Choose an action**: Attack, use a Skill, or Defend
2. 💫 **Action resolves**: damage is calculated using elemental advantages
3. 🔄 **Turn passes** to the opponent
4. 🏆 **Last one standing wins!**

### 🌀 Elemental Advantages

<div align="center">

| Element | Strong Against 💪 | Weak Against 😵 |
|:-------:|:-----------------:|:---------------:|
| 🔥 Fire | 🌿 Nature | 🌊 Water |
| 🌊 Water | 🔥 Fire | ⚡ Lightning |
| 🌿 Nature | 🌊 Water | 🔥 Fire |
| ⚡ Lightning | 🌊 Water | 🪨 Earth |
| 🪨 Earth | ⚡ Lightning | 🌿 Nature |

</div>

> 📝 *Edit this table to match the actual elements and rules in your game.*

---

## 🧙 Playable Characters

<div align="center">

| Portrait | Name | Element | HP | Description |
|:--------:|:----:|:-------:|:--:|:------------|
| <img src="OOP2_game%20Testing/src/assets/spritesheet/Fire%20Wizard/Idle-Sheet.png" width="80"> | **Myrrik Flameheart** | 🔥 Fire | 260 | Volcanic battlemage of pressure and explosive follow-ups. |
| <img src="OOP2_game%20Testing/src/assets/spritesheet/Water%20Wizard/Idle-Sheet.png" width="80"> | **Ondine** | 🌊 Water | 270 | Tide-channeler who controls tempo with flowing strikes and shifting barriers. |
| <img src="OOP2_game%20Testing/src/assets/spritesheet/Nature%20Wizard/Idle-Sheet.png" width="80"> | **Earl Froggington** | 🌿 Nature | 265 | Forest tactician who controls space and saps strength. |
| <img src="OOP2_game%20Testing/src/assets/spritesheet/Steel%20Wizard/Idle-Sheet.png" width="80"> | **Faecyrion Vhaloris** | ⚙️ Steel | 295 | Ironclad duelist using precise, punishing steel. |
| <img src="OOP2_game%20Testing/src/assets/spritesheet/Idk%20Magician/Idle.png" width="80"> | **Caedric Thunderbound** | ⚡ Thunder | 230 | Lightning prodigy of unpredictable, high-risk storms. |
| <img src="OOP2_game%20Testing/src/assets/spritesheet/Wind%20WIzard/Idle-Sheet.png" width="80"> | **Ali Morningstart** | 🌪️ Wind | 250 | Gust incarnate; quick, precise, and disruptive. |
| <img src="OOP2_game%20Testing/src/assets/spritesheet/Light%20Mage/Idle-Sheet.png" width="80"> | **Gwyneth Verdantide** | ✨ Light | 310 | Temple guardian blending bladework with restorative light. |
| <img src="OOP2_game%20Testing/src/assets/spritesheet/Dark%20Wizard/Idle-Sheet.png" width="80"> | **Yuri Moonshade** | 🌑 Dark | 255 | Shadow-touched sorceress of corrosive soul-thread magic. |

</div>

### 🔥 Myrrik Flameheart
| Skill | Type | Effect |
|-------|:----:|--------|
| **Blaze Saber** | Damage | Cuts through one enemy with a burning sword arc. |
| **Fireball** | Damage | Launches a fiery projectile that deals balanced fire damage. |
| **Flame Jet** | Damage | Unleashes a jet of flame that scorches one enemy and heals the caster. |

---

## 📸 Screenshots

<div align="center">

| Main Menu | Character Select |
|:---------:|:----------------:|
| <img src="OOP2_game%20Testing/src/assets/main_menu.png" width="400"> | <img src="OOP2_game%20Testing/src/assets/character_selection.png" width="400"> |

| Battle Screen | Victory Screen |
|:-------------:|:--------------:|
| <img src="OOP2_game%20Testing/src/assets/battle_screen.png" width="400"> | <img src="OOP2_game%20Testing/src/assets/victory_screen.png" width="400"> |

</div>

### 🎬 Title Screen

<div align="center">

<img src="OOP2_game%20Testing/src/assets/maps/splashscreen.png" alt="Primordia Title Screen" width="700">

</div>

---

## 🛠️ Built With

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

</div>

> 📝 *Add or remove badges depending on your tools (e.g., JavaFX, Swing, Maven, Gradle, NetBeans, Eclipse).*

---

## ⚙️ Installation

### 📋 Prerequisites

- ☕ [Java JDK 17+](https://www.oracle.com/java/technologies/downloads/)
- 💻 Any Java IDE (IntelliJ IDEA, Eclipse, NetBeans) *or* a terminal

### 📥 Setup

```bash
# 1. Clone the repository
git clone https://github.com/jnerlherms/Primordia.git

# 2. Move into the project folder
cd Primordia

# 3. Compile the game
javac -d out src/*.java

# 4. Run the game
java -cp out Main
```

> 📝 *Adjust the compile and run commands to match your actual package structure and main class.*

### 💡 Running From an IDE

1. Open the project folder in your IDE.
2. Make sure the **Project SDK** is set to Java 17 or higher.
3. Locate the `Main` class.
4. Click **Run ▶️**.

---

## 🕹️ How to Play

1. **Launch** the game.
2. **Select** your elemental champion.
3. **Battle** your opponent in turns.
4. **Win** by reducing the enemy's HP to zero!

### 🎛️ Controls

| Input | Action |
|:-----:|--------|
| `1` | ⚔️ Basic Attack |
| `2` | ✨ Use Skill |
| `3` | 🛡️ Defend |
| `4` | 🚪 Exit / Forfeit |

> 📝 *Update controls to match your game's actual input scheme.*

---

## 📂 Project Structure

```
Primordia/
├── 📁 src/
│   ├── 📄 Main.java            # Game entry point
│   ├── 📄 Character.java       # Base character class
│   ├── 📄 Battle.java          # Turn-based battle logic
│   ├── 📄 Skill.java           # Skill / ability definitions
│   └── 📁 characters/          # Elemental character classes
├── 📁 assets/                  # Images, GIFs, and README media
├── 📄 README.md
└── 📄 LICENSE
```

> 📝 *Replace with your real file and folder layout.*

---

## 🗺️ Roadmap

- [x] Core turn-based battle system
- [x] Elemental playable characters
- [ ] More characters and elements
- [ ] Status effects (burn, freeze, stun)
- [ ] Single-player vs AI mode
- [ ] Sound effects and music
- [ ] Graphical user interface improvements

See the [open issues](https://github.com/jnerlherms/Primordia/issues) for a full list of proposed features and known bugs.

---

## 🤝 Contributing

Contributions make the open-source community amazing! Any contributions you make are **greatly appreciated**.

1. 🍴 Fork the project
2. 🌿 Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔃 Open a Pull Request

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

---

## 👤 Author

<div align="center">

**jnerlherms**

[![GitHub](https://img.shields.io/badge/GitHub-jnerlherms-181717?style=for-the-badge&logo=github)](https://github.com/jnerlherms)

*Project Link:* [https://github.com/jnerlherms/Primordia](https://github.com/jnerlherms/Primordia)

</div>

---

<div align="center">

### ⭐ If you enjoyed Primordia, give it a star! ⭐

*Made with ☕ and 🔥 in Java*

</div>
