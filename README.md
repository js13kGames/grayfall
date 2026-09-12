# grayfall
а minimalist pixel-art side-scroller where a unicorn restores the stolen rainbow by defeating color-based bosses

# Grayfall

A minimalist pixel-art platformer built for **js13kGames 2026**.

The Color Thief has stolen the rainbow, leaving the world gray. Play as a unicorn, defeat powerful guardians, restore lost colors, and confront the Color Thief.

## Gameplay

Grayfall is built around a simple progression:

**Explore → Fight → Learn → Restore Color → Unlock an Ability → Continue**

The game features **3 levels**:

* **Level 1 — Flame Beast** → Restore RED → Unlock Fireball
* **Level 2 — Dash Fiend** → Restore ORANGE → Unlock Dash
* **Level 3 — The Color Thief** → Restore the Rainbow → Ending

## Features

* Pixel-art side-scrolling platformer
* 3 compact levels
* 3 boss encounters
* Pattern-based boss combat
* Fireball and Dash abilities
* Procedural pixel-art graphics
* Reusable boss and level systems
* HTML5 Canvas
* Vanilla JavaScript
* No external assets or libraries
* Designed for the **13 KB js13kGames limit**

## Boss System

Bosses use a shared state machine:

**IDLE → TELEGRAPH → ATTACK → VULNERABLE**

The player can only damage a boss during its vulnerable window.

Each boss reuses the same core system with different attack patterns, keeping the game lightweight while making each encounter feel distinct.

## Technical Approach

Levels are generated from a small set of parameters rather than hand-authored maps.

Visuals are rendered entirely with Canvas primitives such as rectangles and triangles. No image assets are required.

The game uses a low-resolution **320×180 canvas**, scaled with pixelated rendering for a chunky pixel-art style.

## Tech

* HTML5 Canvas
* Vanilla JavaScript
* Procedural graphics
* No external dependencies

## Goal

Restore the rainbow.

Defeat the Color Thief.

##Если честно, игра выглядит ну супер простой, но мне нравится тот факт, что это я написала (да, из говна и палок, но, это лучше не постить ниче :) )
