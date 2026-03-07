# 🛡️ PolygonX PoGo PvP Filter Generator (v35)

An advanced tool designed for **PolygonX** users to generate highly accurate PvP encounter filters. This generator uses exact Game Master stats and CPM (CP Multipliers) to identify the best possible IV combinations for competitive play.

## 🚀 Features

* **Breakpoint Archetypes:** Generate a "Trio" of filters (Bulk, Mid, and Slayer) to ensure you catch Pokémon that hit specific damage breakpoints while maintaining survival.
* **Precise Math:** Uses the correct "Floored HP" logic used by professional rank checkers (like PvPoke).
* **Multi-Export:** Add dozens of Pokémon to a single `.json` file for easy importing.
* **Family Logic:** Automatically identifies the base form of any Pokémon family to ensure your filters catch the right babies for evolution.
* **League Support:** Full support for Little League (500 CP), Great League (1500 CP), and Ultra League (2500 CP).

## ⚔️ The Archetype System

Unlike standard rank checkers, this tool helps you find "Matchup Flippers":

* **BULK:** The traditional Rank 1 (Maximum Stat Product).
* **MID:** Targets **+5% Attack** compared to Rank 1 while maintaining 90% of the total bulk. Great for general consistency.
* **SLAYER:** Targets **+10% Attack** for aggressive fast-move pressure, but mandates an 80% bulk floor so the Pokémon isn't too glassy.

## 🧬 Smart Form Mapping

Version 35 includes an **Aggressive Form Mapper**. It automatically handles inconsistent naming conventions between PvPoke and backend Masterfiles:

* **Regional Support:** Correctly maps "Alolan", "Galarian", "Hisuian", and "Paldean" forms to their specific internal IDs (e.g., Articuno vs. Articuno Galar).
* **Normalization:** Automatically handles "Alola" vs "Alolan" naming discrepancies to ensure your filters never default to the wrong form.

## 📥 How to Install

1. Go to your <https://zwajton.github.io/polygonx-pvp-filter/>.
2. Create your desired list of Pokémon.
3. Download the `.json` file.
4. In **PolygonX**, go to **Configs > Snipe filters (Very high, high or low prio) > Import** and select the file.

## 🛠️ Built With

* Pure HTML5 / CSS3 / Vanilla JavaScript
* PvPoke GameMaster Data API
* WatWowMap Masterfile Generator