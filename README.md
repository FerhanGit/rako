# 🌲 RAKO — First Person Forest

Hunt monsters through a cursed forest and slay the **God of the End**, king of the monsters,
in the dark heart of the woods.

## ▶️ How to play
Open **`index.html`** in any web browser (double-click it, or use VS Code's *Live Server* /
"Open with Live Server").

## 🎮 Controls
| Action | Key |
|--------|-----|
| Look around | **Mouse** (click once to capture it) |
| Move | **W A S D** |
| Turn | **← →** |
| Attack | **Space** or **Click** |
| Open chest | **E** |
| Fly (with pet) | **F** |

## 🧩 Features
- **First-person 3D** rendered in pure HTML5 canvas — no libraries, no internet needed.
- **Forest world** with your cozy wooden **cabin** as a safe zone (heals HP + hunger).
- **Survival**: a hunger bar drains over time — eat 🍖 food found on the ground or dropped by monsters.
- **Chests**:
  - 📦 Normal chests — random rewards (feast, +max HP, or +damage).
  - 🐉 **Rako Chest** (golden, rare, deep in the forest) — grants a **Skyling pet**.
- **Flying pet**: with the Skyling, press **F** to fly for **10 seconds, once every minute**.
  While flying you soar over the trees, move faster, and monsters can't hit you.
- **Boss**: the God of the End enrages as he weakens and hurls shadow bolts below half health.
- **Atmosphere & feel**: procedural sound effects (no files), screen shake on impacts, a red
  hurt-flash, a moonlit night sky, drifting fireflies, edge vignette, and a perspective ground
  grid so you can feel yourself moving through the forest.
- **Day/night cycle**: 2-minute safe days, 90-second nights when the monsters hunt.
- **Time Crystal** (from a Rako Chest): press **T** to freeze every enemy for 5s (60s cooldown).
- **Enterable 3D cabin**: press **E** at your cabin to step inside a real 3D room and shelter.
- **Lobby**: an account (name, total wins, "playing since" date), a **Play** menu with
  **Easy / Normal / Hard** difficulty, and **Settings** for music and render quality.

## 🔒 Secret codes
A discreet **codes** button sits in the bottom-right of the lobby. Codes are saved per browser:
- **`kora`** — every run starts with a **Rocky Chest** (mine it with **E** for Stone=1, Bedrock=10,
  Amethyst=50, Diamond=100 points) and a **Trade Table** (spend points: 🌶 Hot Pepper=1,
  🗡 Pisto Sword=10 (2× damage), 🧊 Ice Ward=50 (press **G**: freeze + untouchable 10s / 50s cd),
  🚀 RPG=100 (press **R**: one-shot the King)).
- **`ati`** — unlocks an **🛠 Admin** button in-game: god mode, toggle fly, give/spawn anything
  (monsters, chests, food, King…), time of day, +stats, ban all monsters.
- **`secretcode`** — every run starts with **+150 max HP**.

The cabin can be entered (press **E**) into a **2D top-down decorated room** — but shelter longer
than **5 minutes** and the monsters break in and throw you out. The map is large; the boss waits
in a **nightmare city of cathedral spires** with gaunt giants and a towering god in the sky.
Monsters in the **nightmare city hunt day and night** (not just at night).

## 👥 Co-op & leaderboards
From **PLAY** you pick a difficulty, then **how many other players** (Solo, or 1–6). Those players are
**local AI teammates** that fight alongside you, take damage, can go down and revive, and score their
own kills. The lobby's **Friends** list lets you add names (saved in your browser) that are used to
name your teammates, and **Leaderboards** is a ranked board (your place, name, wins and time played)
against persistent rivals, plus the last match's kill scoreboard. Teammates get **random names**, and
they **fight, open chests, and explore** the map on their own.

## 🗺 Map (fog of war)
Press **M** (or the top-bar button) to open the map. It starts **black** — you only see places you've
**explored**. Walking around (and your teammates roaming) reveals the terrain; landmarks like 🏠 home,
🏰 the stronghold, 👑 the city, and unopened chests appear once you've been near them.

> Note: this game is a single local HTML file with no server, so it can't do true online multiplayer
> (matchmaking / inviting real people over the internet). The "other players" are AI teammates and
> Friends are local — real online play would require a backend server.

## 🐺 Bunnies, wolves & the Entities
**🐰 Bunnies** hop around the forest — kill them with your sword for **🥩 meat**. **🐺 Wild wolves**
will **bite you** on sight, but if you have meat, walk up and press **P** to feed and **tame** one.
A tamed wolf becomes your **pet**: it follows and protects you, and hunts down the **🕸 Entities** —
black creatures that stalk and attack you across the map.

## 🏰 The Stronghold
A walled stone compound stands in the forest. Walk through its south gate and **defeat all the
guards** inside to unlock the **Stronghold Chest**, which grants the **Stone Sword** (heavier,
harder-hitting attacks). Its guards are hostile around the clock.

## 🎵 Music
The Settings → Music toggle plays background music. To use the *Roblox 3008 — 1 Hour* track,
save your own audio file as **`music.mp3`** next to `index.html` (copyrighted audio isn't bundled).
If no `music.mp3` is present, a soft procedural ambient loop plays instead. Wins, your name, and
settings are saved in the browser's local storage.

## 📁 Project structure
```
Rako-Game/
├─ index.html   ← the entire game (HTML + CSS + JS)
└─ README.md    ← this file
```

Made with Claude Code.
