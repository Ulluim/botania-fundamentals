# 🗺️ Botania Fundamentals Roadmap

Welcome to the official roadmap for **Botania Fundamentals**! This document outlines the planned trajectory for future updates. Our primary focus is divided into three core pillars: **Extreme Performance**, **Quality of Life (QoL)**, and **Flora Rebalancing**.

---

## 🚀 Phase 1 — Performance Optimization (WIP)
Botania can be heavily taxing on servers in massive modpacks. This phase aims to introduce aggressive, configurable optimizations to save server TPS and client FPS without compromising vanilla Botania mechanics.

- [ ] **Hopperhock "Smart Delay" Optimization:** Reduce the frequency of AABB world scans.
- [x] **Spreader Logic Optimization:** (Released in V1.2.2) Spreaders skip expensive checks when idle.
- [ ] **Corporea Network Caching:** Add a temporal caching system to the Corporea Index to prevent massive lag spikes when querying thousands of chests.
- [ ] **Global Particle Reduction:** A client-side config to halve or disable purely cosmetic particles (like Mana Pool passive effects) for a massive FPS boost in large bases.

---

## ⚙️ Phase 2 — Mechanics & Quality of Life (QoL)
To prevent the "spamming" of entities (like placing 100 mana pools), this phase will allow players to linearly scale the power of fundamental blocks via config multipliers.

- [ ] **Massive Spreader Capacities:** 
- [ ] **Adjustable Mana Pool Capacities:** Inject a multiplier to allow single Mana Pools to hold tens of millions of mana, saving physical space and rendering load.
- [ ] **Mana Ring/Tablet Buffs:** Capacity multipliers for portable mana storage to match the new massive pools.
- [ ] **Hyperactive Pure Daisy:** Configurable option to drastically reduce the 60-second wait time for Livingwood/Livingrock (e.g., down to 10-15 seconds).
- [ ] **Automated Runic Altar:** Allow the Runic Altar to autonomously craft its recipe if the ingredients, livingrock, and mana requirements are met, removing the need to manually right-click with a Wand of the Forest.

---

> **Note:** This roadmap is a living document. Features may be added, removed, or reprioritized based on community feedback and technical constraints.
