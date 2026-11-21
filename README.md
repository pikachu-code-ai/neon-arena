# neon-arena# 🛸 NEON ARENA 3D — Cyberpunk Hover-Tank Battle

**NEON ARENA 3D** is a fast-paced 3D cyberpunk arena shooter built in single-file HTML5 using **Three.js** and procedural **Web Audio API** sound synthesis. Pilot your vector plasma hover-tank across high-contrast grid arenas, dodge enemy crossfire, collect tactical power-ups, phase-dash to absorb damage, and annihilate hostile waves up to the ultimate Apex Core Boss!

---

## ✨ Key Features

* **3D Perspective & Dynamic Lighting:** Powered by Three.js (`r128`), featuring a dark vector grid plane, translucent boundary walls, randomized monolith pillars, exponential fog, and real-time lighting.
* **360° Independent Turret Controls:** Dual-barrel plasma cannon turret rotates independently from the hover chassis, guided by mouse raycasting, auto-aim assistance, or dual virtual joysticks.
* **5 Tactical Missions + Boss Arena + Endless Siege:**
  * Fight through 5 distinct level scenarios featuring dynamic pillar layouts and escalating hostile rosters.
  * Face **THE APEX CORE** in Level 5—a massive multi-ring cyber-fortress with orbital shield rings.
  * Survive infinite waves in **Endless Siege** mode.
* **5 Hostile AI Enemy Classes:**
  * **Scout Strikers:** Fast crimson pyramid drones that swarm and fire light plasma.
  * **Cyber Tanks:** Medium hover units with rotating turrets.
  * **Rail Snipers:** Long-range obelisks that charge and telegraph high-speed railbeams.
  * **Heavy Juggernauts:** Armored hex tanks firing 3-way spread volleys.
  * **The Apex Core (Boss):** Central citadel emitting rotating bullet-hell plasma patterns.
* **Power-Ups & Tactical Drops:**
  * **3-Way Spread:** Triple plasma stream spray.
  * **Piercing Railbeam:** High-velocity golden beam that punches through multiple hostiles.
  * **Aegis Shield Restore:** Instantly recharges +2 shield pips.
  * **Overdrive Boost:** Grants +50% EMP Overdrive energy.
  * **Score Crystals:** Magnetized glowing drops that boost scores with up to 16X combo multipliers.
* **Deflection & Overdrive Mechanics:**
  * **Phase Dash (`Shift` / `Space` / Right-Click):** Sudden high-speed thruster surge with invulnerability frames that absorbs/deflects incoming fire for `+150 PHASE DODGE` points.
  * **Hyper EMP Overdrive (`Q` / `E`):** Golden expanding 3D EMP dome that vaporizes enemy projectiles into score crystals while damaging and stunning all nearby hostiles.
* **Procedural Web Audio SFX:** Zero external audio assets required. Generates laser blasts, railbeams, ricochets, dash whooshes, shield hits, explosion noise bursts, and victory fanfares directly via Web Audio API.

---

## 🏁 Mission Roster

| Level | Mission Name | Tactical Objective | Layout | Threat Roster |
| :--- | :--- | :--- | :--- | :--- |
| **LVL 1** | **Neon Grid** | Eliminate `12` Hostiles | Open Tactical Pillars | Scout Strikers & Cyber Tanks |
| **LVL 2** | **Pillar Maze** | Eliminate `18` Hostiles | Dense Cover Labyrinth | Rail Snipers & Cover Flankers |
| **LVL 3** | **Laser Foundry** | Eliminate `24` Hostiles | Laser Crossfire Corridors | Fast Strikers & Rail Beams |
| **LVL 4** | **Siege Citadel** | Eliminate `30` Hostiles | Fortified Siege Arena | Heavy Juggernauts & Swarm Escorts |
| **LVL 5** | **Apex Core** | Destroy **The Apex Core** | Central Fortress Chamber | Boss Core & Shield Generators |
| **ENDLESS**| **Endless Siege** | Survive Infinite Waves | Procedural Recycling | Continuous Escalating Swarms |

---

## 🎮 Controls

### Desktop Controls

| Key / Input | Action |
| :--- | :--- |
| **`W` / `S` / `A` / `D`** | Move Tank Chassis (North / South / West / East) |
| **Mouse Cursor** | 360° Turret Aiming (with Floor Laser Sight) |
| **Left-Click** | Fire Twin Plasma Cannons |
| **`Shift` / `Space` / Right-Click** | **Phase Dash** (Invulnerable Thruster Dodge) |
| **`Q` / `E`** | Trigger **Hyper EMP Overdrive** (at 100%) |
| **`P` / `Esc`** | Pause / Resume Battle |

### Mobile Touch Controls

* **Left Virtual Joystick:** Tank Chassis Directional Movement.
* **Right Virtual Joystick:** 360° Turret Aiming.
* **`⚡ PHASE DASH` Button:** Executes Phase Dodge.
* **`🔥 PLASMA CANNONS` Button:** Manual trigger (when Auto-Fire is OFF).
* **`OVERDRIVE` Button:** Activates Hyper Overdrive when charged to 100%.

---

## 🛠️ Technical Details

* **Bundle Type:** Fully self-contained HTML5 file (`neon_arena_3d.html`) containing CSS styling, WebGL rendering logic, 3D math engines, game loop, and Web Audio synthesizer.
* **Libraries:** Three.js (`r128`) CDN.
* **Input Engine:** Dual-axis virtual joystick touch handlers alongside pointer lock raycasting for high-precision desktop aiming.

---

## 🚀 Quick Start

1. Download or save `neon_arena_3d.html`.
2. Double-click to open in any modern WebGL-compatible web browser (Chrome, Safari, Firefox, Edge).
3. Select your desired battle arena and click **▶ ENGAGE HOVER-TANK**!
