<h1 align="center">🧑‍🌾 VillagerLimiter</h1>

<p align="center">
  <b>Lightweight performance plugin that limits villagers per chunk to stop server lag</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.21+-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Paper%20%7C%20Spigot-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Performance-Optimized-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p>

---

## 🚀 Overview

**VillagerLimiter** automatically limits the number of villagers per chunk, preventing the server lag caused by overbred villager farms.

* ⚡ Lightweight, budget-limited enforcement (10ms max per cycle)
* 🧹 Gradual removal instead of mass deletion
* 🌍 Per-world control
* 📊 Built-in stats and debug tools

Built for servers that need **breeder farms without the TPS hit**.

---

## ✨ Key Features

### ⚡ Per-Chunk Limiting

* Configurable maximum villagers per chunk
* Enforced on a strict time budget so it never freezes the server

### 🧹 Gradual Removal

* Removes excess villagers in small batches per cycle
* Avoids lag spikes from mass entity deletion

### 🌍 Per-World Control

* Enable the limiter only on the worlds you choose

### 🥚 Spawn Egg Toggle

* Optionally allow spawn eggs to bypass the limit

### 📊 In-Game GUI & Stats

* Live stats through `/villager gui`
* Track cached chunks, top overpopulated chunks, and total removals

---

## 🎮 Commands

```
/villager reload
/villager stats
/villager chunk
/villager top
/villager debug
/villager gui
/villager tpchunk <world> <x> <z>
```

---

## ⚙️ Permissions

| Permission                  | Description                              | Default |
| ---------------------------- | ----------------------------------------- | ------- |
| `villagerlimiter.reload`     | Allows using `/villager reload`           | op      |
| `villagerlimiter.tpchunk`    | Allows teleporting to chunks              | op      |

---

## 📦 Installation

1. Drop `VillagerLimiter.jar` into your `plugins` folder
2. Restart the server
3. A default `config.yml` is generated automatically
4. Adjust `villagerLimit`, `checkInterval`, and `enabledWorlds` to taste

---

## 🔧 Requirements

* Java 21+
* Paper / Spigot 1.21+

---

## 🧪 Compatibility

* ✔ Paper
* ✔ Spigot
* ✔ Purpur

---

## 👨‍💻 Developer

**GianniHz**

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🚀 Use it on your server
* 💡 Suggest improvements

---

## 📜 License

Private plugin — documentation public only.

---
