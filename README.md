# UnstableCore
**The definitive plugin for bringing the Unstable SMP experience to your Minecraft server.**

UnstableCore is a high-octane, SMP-focused plugin designed for chaos, high-stakes warfare, and advanced mechanics. Inspired by the *Unstable Universe*, this plugin adds dimension-tearing, orbital weaponry, and advanced combat bots to your server.

---

## 🚀 Key Features

| Mechanic | Description |
| :--- | :--- |
| **Orbital Strikes** | Call down devastating TNT strikes with `setSource` attribution to bypass damage immunity. |
| **Pearl Cannon** | Tactical teleportation arrays for base infiltration and rapid mobility. |
| **Chunk Ban System** | Enforce "Chunk Bans" using persistent shulker-entity triggers to lock down enemy territory. |
| **Fighter AI Bots** | Citizens-powered combat bots with dynamic difficulty (1-5), shield-breaking, and healing routines. |
| **UnderWorld Dimension** | A custom dimension featuring medieval fortresses, jagged spires, and guarded towers. |
| **Far Lands Glitch** | Procedural "Corner Far Lands" generation with massive walls, vertical shafts, and horizontal tunnels. |
| **Soul Link System** | Automated stasis-teleportation; save yourself from death with a 1-heart emergency link. |
| **Proximity Discovery** | Stealth-focused mechanics: death messages and achievements are restricted to a 100-block radius. |

---

## 📜 All Commands

| Command | Usage | Description |
| :--- | :--- | :--- |
| `/nick` | `/nick <name|reset>` | Set your nickname. |
| `/immortal` | `/immortal [player]` | Toggle immortality. |
| `/stasis` | `/stasis [list|remove|tp|rename]` | Manage stasis chambers. |
| `/unstable` | `/unstable <subcommand>` | Admin control for UnstableCore. |
| `/skin` | `/skin <player> [target] | reset` | Spoof your skin. |
| `/orbital` | `/orbital <nuke|stab>` | Orbital strike weaponry. |
| `/cannon` | `/cannon <location|save> <args>` | Pearl cannon management. |
| `/fakeplayers` | `/fakeplayers <spawn <amt> [diff]|clear>` | Spawn/clear fighter AI bots. |
| `/chunkban` | `/chunkban give` | Get chunk ban shulker boxes. |
| `/wolf` | `/wolf` | Get the Wolf Pack Summoner rod. |
| `/soullink` | `/soullink [remove]` | Set/Remove Soul Link. |
| `/farlands` | `/farlands` | Teleport to the Far Lands dimension. |

---

## ⚠️ Requirements & Setup
1. **CitizensAPI** (2.0.42-SNAPSHOT) and **ProtocolLib** (5.4.0) are required.
2. **Dimension Generation**: Allow the plugin to auto-generate the `UnderWorld` and `FarLands` folders on first boot.
3. **World Cleanup**: If you update generation parameters, delete the respective world folder to force a re-generation.

---

*Built for Minecraft 1.21.11. Experience the Unstable Universe.*
