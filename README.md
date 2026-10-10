<div align="center">

<img src="OOP2_game%20Testing/src/assets/banner.png" alt="Primordia Banner" width="100%">

# PRIMORDIA

### *Where the elements clash and only one remains.*

A turn-based elemental duel game for your desktop. Pick a champion, read the matchup, and outlast your opponent.

![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Genre](https://img.shields.io/badge/Genre-Turn--Based_Battle-8A2BE2?style=for-the-badge)
![Players](https://img.shields.io/badge/Players-1--2-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In_Development-brightgreen?style=for-the-badge)

[Play](#-play-in-3-steps) •
[Game Modes](#-game-modes) •
[How to Play](#-how-to-play) •
[Champions](#-the-eight-champions) •
[Elements](#-elements-who-beats-who) •
[Tips](#-tips-for-winning) •
[Help](#-having-trouble) •
[Credits](#-credits)

</div>

---

## 📖 What is Primordia?

In the beginning, there were only the elements. Now they fight for dominance.

Primordia is a fast, strategic duel game. Two fighters take turns casting skills at each other. Every champion has three skills, a pool of mana to spend on them, and a weakness the other side can exploit. There are no combos to memorize and no reflexes to train: you win by choosing the **right skill at the right time**, spending mana wisely, and picking fights where the elements favor you.

- ⚔️ **Easy to learn.** Press `1`, `2` or `3` to cast a skill.
- 🧠 **Deep enough to master.** Elemental matchups, mana budgeting, poison and healing all matter.
- 🔥 **8 champions**, each with their own element, backstory, and three unique skills.
- 🎮 **3 ways to play:** local two-player Versus, endless Survival, and a speedrun-style Arcade.
- 🏆 **Leaderboards** for your best Survival scores and fastest Arcade clears.

---

## 🚀 Play in 3 steps

Primordia runs on **Windows, macOS and Linux**. All you need is Java.

**1. Install Java 17 or newer.**
Any recent JDK works, such as [Adoptium Temurin](https://adoptium.net/). To check, open a terminal and run `java -version`.

**2. Get the game.**
Click the green **Code** button on this page and choose **Download ZIP**, then unzip it. Or, if you use Git:

```bash
git clone https://github.com/jnerlherms/Primordia.git
```

**3. Build and run it.**
Open a terminal inside the folder named **`OOP2_game Testing`** and run:

```bash
# Build (one time)
javac -encoding UTF-8 -d out -sourcepath src src/main/Main.java

# Run on macOS / Linux
java -cp "out:src:../Resources" main.Main

# Run on Windows (Command Prompt or PowerShell)
java -cp "out;src;..\Resources" main.Main
```

The title screen should appear. Press **START** and pick a mode.

> 💡 **Prefer an IDE?** Open the `OOP2_game Testing` folder in IntelliJ IDEA, set the Project SDK to Java 17 or newer, and run the `main.Main` class.
>
> ⚠️ Always start the game from inside the `OOP2_game Testing` folder. The game reads and saves its leaderboard files relative to it.

---

## 🎮 Game Modes

After **START**, choose how you want to fight.

| Mode | Players | What you do |
|:-----|:-------:|:------------|
| **⚔️ Versus** | 2 (same computer) | A classic duel. Each player picks a champion, then you take turns on the same keyboard and mouse. First to win 2 rounds takes the match. |
| **♾️ Survival** | 1 | Fight an endless chain of random opponents. Every win scores points and heals you a little, but the opponents get smarter as you go. How far can you get? |
| **🏁 Arcade** | 1 | Beat all 7 other champions in a row. A timer runs the whole time, and a full clear goes on the speedrun leaderboard. Lose a match and the run is over. |

The main menu also has **LEADERBOARD**, **SETTINGS**, **CREDITS** and **QUIT**.

---

## 🎯 How to Play

### Controls

| Input | What it does |
|:-----:|:-------------|
| `1` `2` `3` | Cast skill 1, 2 or 3 (you can also click the skill buttons) |
| `←` `→` `↑` `↓` + `Enter` | Move around and confirm on the character select screen |
| **Exit button** (top-right corner of the battle screen) | Pause the battle: Resume Game, Main Menu, or Quit Game |
| `Esc` | Close the pause menu or Settings screen and go back |
| Mouse | Click any menu button |

### A match, step by step

1. **Choose your champion.** The preview shows each skill's mana cost and damage.
2. **Take turns.** You and your opponent alternate. On your turn, cast one skill.
3. **Watch the clock.** Each turn lasts **10 seconds**. Act quickly for a small damage and healing bonus. If time runs out, your turn is skipped (you still regain mana).
4. **Win rounds.** Reduce your opponent's HP to zero to win the round. **Win 2 rounds** to win the match (best of 3). This applies to Versus and Arcade. In Survival, each opponent is a single round.

### Health and mana

- **HP** is your health. At zero, you lose the round.
- **MP (mana)** pays for skills. Stronger skills cost more, so you can't cast the big ones every turn.
- You regain **25 MP** every time your opponent takes a turn, so expect to alternate between cheap and expensive skills.

### What skills do

Skills come in a few flavors. Your champion's mix is what makes them play differently.

- **Damage:** hurts the enemy right now.
- **Poison / burn / shock:** keeps damaging the enemy at the start of their turns for a few turns after the hit.
- **Self-heal:** some attacks restore a bit of your own HP.
- **Shield and defense:** protect or heal you instead of attacking.

> Hitting an enemy who is **poisoned** also gives your damage a small bonus (+8%).

---

## 🧙 The Eight Champions

Every champion has a unique element, health, mana pool, and playstyle. You can see the same information in the character select screen.

| Champion | Element | HP | MP | Playstyle |
|:---------|:-------:|:--:|:--:|:----------|
| **Myrrik Flameheart** | 🔥 Fire | 260 | 215 | Pressure and burn damage |
| **Ondine** | 🌊 Water | 270 | 215 | Steady tempo with a little healing |
| **Earl Froggington** | 🌿 Nature | 265 | 230 | Poison, attrition and defensive stances |
| **Ali Morningstart** | 🌪️ Wind | 250 | 235 | Fast, precise strikes |
| **Caedric Thunderbound** | ⚡ Thunder | 230 | 240 | High-risk burst damage |
| **Gwyneth Verdantide** | ✨ Light | 310 | 200 | The toughest: shields and regeneration |
| **Faecyrion Vhaloris** | ⚙️ Steel | 295 | 205 | Sturdy controller with explosive tricks |
| **Yuri Moonshade** | 🌑 Dark | 255 | 220 | Draining magic and a huge finisher |

<details>
<summary><b>📜 Skill lists for every champion (click to expand)</b></summary>

<br>

Numbers in brackets are the **MP cost**.

**🔥 Myrrik Flameheart** *(a volcanic battlemage who tempers wildfire into disciplined strikes)*
1. **Blaze Saber** [45]: a burning sword arc.
2. **Fireball** [68]: a fiery projectile that also leaves the enemy burning.
3. **Flame Jet** [88]: a powerful jet of flame that heals you a little.

**🌊 Ondine** *(channels tides and pressure into disciplined bladework)*
1. **Tidal Shot** [44]: a swift pressurized water shot.
2. **Water Beam** [67]: a concentrated beam that heals you a little.
3. **Frigid Current** [88]: a dragging current frozen into a potent strike.

**🌿 Earl Froggington** *(a forest tactician who favors attrition)*
1. **Thorn Swipe** [45]: thorned vines that damage and poison. In defense stance, a quick dart that only poisons.
2. **Frog Kiss** [65]: a venom-laced dart with very strong poison.
3. **Natures Embrace** [85]: heal and take a defensive stance. Use it again to drop the stance.

**🌪️ Ali Morningstart** *(moves like a gust incarnate: quick, precise, disruptive)*
1. **Gale Cut** [42]: a razor gust.
2. **Judgement Cyclone** [62]: a spinning wind current launched at the enemy.
3. **Tempest Slash** [82]: a beam of wind slashes that pierces the target.

**⚡ Caedric Thunderbound** *(a restless lightning prodigy who loves unpredictable finishes)*
1. **Lighting Burst** [48]: a jagged shock that lingers briefly.
2. **Thunder Call** [70]: a balanced bolt from the sky.
3. **Plasma Bolt** [95]: an unstable bolt that hits very hard.

**✨ Gwyneth Verdantide** *(a temple guardian blending bladework with restorative light)*
1. **Light Sword** [42]: a radiant slash that explodes on impact.
2. **Halo of Aegis** [60]: a shield plus steady regeneration for yourself.
3. **Dawn Piercer** [80]: a focused beam of concentrated light.

**⚙️ Faecyrion Vhaloris** *(an ironclad duelist who bends steel into precise strikes)*
1. **Iron Breaker** [40]: a heavy steel chain whip.
2. **Explosive Dart** [65]: an exploding steel dart that heals you a little.
3. **Spiky Snack** [90]: eat a snack, then pierce the enemy with steel spines.

**🌑 Yuri Moonshade** *(a shadow-touched sorceress whose magic erodes resolve)*
1. **Shadow Tail** [44]: a shadowy tail whip.
2. **Mystic Flame** [66]: flames that hurt the enemy and heal you.
3. **Sacrificial Fire** [98]: a flame overflowing with dark energy.

</details>

---

## 🌀 Elements: Who Beats Who

Every champion is **weak to two elements**. If you attack an enemy who is weak to your element, your skills deal **24% extra damage**. The game also shows a colored indicator in battle, green when you have the advantage and red when the enemy does.

| Element | Hits hard against 💪 | Hurt badly by 😵 |
|:-------:|:--------------------:|:----------------:|
| 🔥 Fire | Nature, Steel | Water, Wind |
| 🌊 Water | Fire, Steel | Nature, Light |
| 🌿 Nature | Water, Light | Fire, Steel |
| ⚙️ Steel | Nature, Wind | Water, Fire |
| ⚡ Thunder | Wind, Dark | Wind, Dark |
| 🌪️ Wind | Fire, Thunder | Thunder, Steel |
| ✨ Light | Water, Dark | Dark, Nature |
| 🌑 Dark | Thunder, Light | Light, Thunder |

> Some matchups go both ways. Thunder and Dark, and Light and Dark, can each exploit the other.

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

## 🏟️ The Arenas

The game rotates between three pixel-art arenas, so no two fights have to look the same.

<div align="center">

| Graveyard | Castle Hall | Forest |
|:-----------------:|:-----------:|:-----------------:|
| <img src="OOP2_game%20Testing/src/assets/maps/backgrounds/Battleground1/Bright/Battleground1.png" width="280"> | <img src="OOP2_game%20Testing/src/assets/maps/backgrounds/Battleground2/Bright/Battleground2.png" width="280"> | <img src="OOP2_game%20Testing/src/assets/maps/backgrounds/Battleground3/Bright/Battleground3.png" width="280"> |

</div>

---

## 💡 Tips for Winning

- **Check the matchup first.** A 24% bonus adds up fast. If your champion is weak to theirs, play it safe and lean on healing.
- **Don't burn all your mana.** Your big skill costs 80 to 98 MP, but you only regain 25 per turn. Open with cheaper skills and save the finisher for when it counts.
- **Be quick, not frantic.** Acting early in the 10-second timer gives a small bonus, but a skipped turn is worse than a hurried choice.
- **Poison pays off.** It keeps damaging after you stop casting, and attacking a poisoned target adds +8% damage.
- **Heal at the right moment.** Healing and shield skills get a small boost once your HP drops to 40% or below, but don't wait so long that one hit knocks you out.
- **In Survival, protect your HP.** You only recover **30 HP** between rounds, and each win scores **100 + your remaining HP + 10 × the round number**. Winning with lots of health left is worth far more.
- **In Arcade, speed matters.** The clock never stops between fights, so favor skills that end matches quickly.

---

## 🏆 Leaderboards

- **Survival:** ranked by score. Reach as high a round as you can.
- **Arcade:** ranked by clear time. Beat all 7 other champions as fast as you can, then enter your name.

Open them any time from **LEADERBOARD** on the main menu.

---

## ⚙️ Settings

Open **SETTINGS** from the main menu to adjust **Background Music** and **Sound Effects**. Each has its own on/off toggle and volume slider.

---

## 🔧 Having Trouble?

| Problem | Try this |
|:--------|:---------|
| `javac` or `java` is "not recognized" | Java isn't installed or isn't on your PATH. Install JDK 17+ and open a **new** terminal. |
| Lots of compile errors when building | Your Java is probably too old. Run `java -version`. Primordia needs **Java 17 or newer**. |
| The game opens but images or text look wrong | Make sure you ran it from inside the `OOP2_game Testing` folder and used the full `-cp` shown above, including `src` and `..\Resources` (or `../Resources`). |
| There's no title bar or close button | That's normal. Primordia runs in a borderless full-screen-style window. Choose **QUIT** on the title screen, or use the exit button in the top-right corner of a battle and pick **Quit Game**. |
| No sound | Check your system's audio output, then check **SETTINGS** in the game. |
| Leaderboard won't save | Start the game from the `OOP2_game Testing` folder, and make sure the folder isn't read-only. |

Found a bug? Please [open an issue](https://github.com/jnerlherms/Primordia/issues) and tell us what you did and what you expected.

---

## 🗺️ What's Next

- [x] Eight playable elemental champions
- [x] Versus, Survival and Arcade modes
- [x] Leaderboards for Survival and Arcade
- [x] Music and sound effects
- [ ] More champions and elements
- [ ] More arenas
- [ ] Further polish and balance changes

---

## 👥 Credits

Primordia was made by **The Elemental Council**.

| Name | Role |
|:-----|:-----|
| **Johan Borinaga** | Project Manager |
| **Faena Ciaron Flores** | Project Manager |
| **Mike Juneil Dolores** | Sound Manager |
| **Jon Erlo Hermosa** | Game Manager |
| **Earl Domingo** | Character Design Manager |

The in-game **CREDITS** screen shows the full team.

---

## 🧑‍💻 For Developers

<details>
<summary><b>Project layout and technical notes (click to expand)</b></summary>

<br>

Primordia is written in **pure Java** (Swing/AWT), with no external libraries.

```
Primordia/
├── OOP2_game Testing/
│   └── src/
│       ├── main/Main.java            # Entry point
│       ├── engine/                   # Game logic: panels, combat, bot AI, menus
│       └── assets/
│           ├── data/                 # characters.json, SFX map, leaderboards
│           ├── maps/                 # Menu screens and battle backgrounds
│           ├── spritesheet/          # Character animations
│           ├── BattleUI/             # Battle interface art
│           ├── SoundManager/         # Music and sound effects
│           └── Utility/              # Shared UI helpers, fonts, round manager
├── Resources/fonts/                  # Pixel fonts used by the UI
├── docs/COMBAT_SYSTEM.md             # Combat reference (see note below)
└── class-diagram.puml                # Class diagram (PlantUML)
```

**Where to tweak things**

- **Champions, HP, MP, skills and weaknesses:** `OOP2_game Testing/src/assets/data/characters.json`. The game reads these values at startup.
- **Damage and healing math:** `engine/CombatBalance.java`.
- **Bot behavior and difficulty:** `engine/BotAI.java`.
- **Round rules** (best of 3): `assets/Utility/RoundManager.java`.

**Combat quick reference:** damage is `skill power × timing multiplier (0.92–1.10) × poison bonus (1.08) × element bonus (1.24)`, capped at 100 per hit. Mana regenerates 25 per turn. Turns last 10 seconds.

> 📝 `docs/COMBAT_SYSTEM.md` describes an earlier balance pass (for example, different HP values and formula). When it disagrees with `characters.json` or `CombatBalance.java`, the code is the source of truth.

**Building without an IDE** uses the same commands as [Play in 3 steps](#-play-in-3-steps). The build needs Java 17 or newer.

**Contributing:** fork the repo, create a feature branch, and open a pull request. Please keep `characters.json` and the in-game text in sync when you rebalance a champion.

</details>

---

<div align="center">

### ⭐ If you enjoy Primordia, give it a star! ⭐

*Made with ☕ and 🔥 in Java*

</div>
