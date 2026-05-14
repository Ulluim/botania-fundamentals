<img width="1024" height="434" alt="Botania_Fundamentals_optimized" src="https://github.com/user-attachments/assets/3e295ddb-ed9d-4329-a49b-3c70e8b3c942" />

# 🌿 Botania Fundamentals

![Minecraft Version](https://img.shields.io/badge/Minecraft-1.20.1-brightgreen)
![Mod Loader](https://img.shields.io/badge/Loader-Forge-orange)
![Version](https://img.shields.io/badge/Version-1.2.2_Beta-blue)
![License](https://img.shields.io/badge/License-MIT-purple)

**Botania Fundamentals** is a lightweight, strictly server/client-safe Forge addon designed to dramatically enhance the early-to-mid game of [Botania](https://botaniamod.net/). Created for massive modpacks, this mod removes the tedious grinding, buffs underperforming generating flora, and implements critical performance optimizations to save your server's TPS.

---

## ✨ Features & Tweaks

### ⚡ Enhanced Generating Flora
*   **Endoflame Rebalance:** Multiplies mana generation significantly (configurable) to make early-game automation feel rewarding rather than a chore.
*   **Hydroangeas & Thermalilies:** Buffed baseline generation (configurable multiplier). 
*   **Immortal Hydroangeas:** Passive flowers are back to their glory days. Hydroangeas no longer decay and die over time (can be toggled off in config).

### ⚙️ Automation & Quality of Life (QoL)
*   **Petal Apothecary Auto-Refill:** If placed adjacent to or above a water source block (or waterlogged block), the Apothecary will instantly and automatically refill itself when empty.
*   **Terrasteel Discount:** Reduces the absurdly high vanilla mana cost for Terrasteel creation (configurable).
*   **Integrated Documentation:** All features and tweaks are seamlessly integrated into the **Lexica Botania** in-game via a custom Patchouli category (Check the *Index* tab!).

### 🚀 Server Performance & Optimization
*   **Spreader Logic Optimizations:** Spreaders skip expensive line-of-sight and receiver checks when idle (no mana) or when their target Mana Pool is completely full.

---

## 🛠️ Configuration
Every single feature in Botania Fundamentals is fully customizable. Upon launching the game, a file named `botaniafundamentals-common.toml` will be generated in your `config` folder.

You can adjust:
- Specific mana generation multipliers for all affected flowers.
- The Terrasteel mana cost multiplier.
- Toggling the Apothecary auto-refill feature.

---

## Documentation

* Full documentation available in the [Wiki](https://github.com/TUUSUARIO/botania-fundamentals/wiki).
---

## 📥 Installation
1. Ensure you have **Minecraft Forge 1.20.1** installed.
2. Download the latest version of [Botania](https://www.curseforge.com/minecraft/mc-mods/botania).
3. Drop the `botaniafundamentals-X.X.X.jar` file into your `mods` folder.
4. *(Optional)* Install **Sinytra Connector** if you are playing in a Fabric-bridged environment. This mod's Mixins have been strictly written without `@Shadow` dependencies to guarantee 100% cross-loader compatibility.

---

## 📝 Credits & Attribution
*   **Ulluim:** Creator and Lead Developer of *Botania Fundamentals*.
*   **Vazkii & The Botania Team:** For creating the masterpiece that is Botania. All base concepts, assets, and the Lexica Botania foundation belong to them. This is an unofficial addon.

## 📄 License
This project is licensed under the MIT License - feel free to use it in any modpacks!
