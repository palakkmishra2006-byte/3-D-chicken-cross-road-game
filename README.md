# Voxel Crossy Road - Gesture Controlled 🐔🚗

A 3D low-poly clone of the popular game **Crossy Road** built with Three.js, featuring real-time, webcam-based hand tracking controls powered by Google MediaPipe. 

Guide the chicken across busy roads and safe grass clearings using only your hand gestures!

---

## 🎮 How to Play

The game can be controlled via your computer's webcam or standard keyboard layout.

### 🎥 Hand Gesture Controls
Hold up **exactly one finger** at a time in front of your webcam to move:
* **Index Finger Only** ☝️ → Move Forward (▲)
* **Middle Finger Only** 🖕 → Move Backward (▼)
* **Ring Finger Only** 💍 → Move Left (◀)
* **Pinky Finger Only** 🤙 → Move Right (▶)

> **Note:** The game includes a gesture cooldown system to prevent infinite jumping. To make multiple jumps in the same direction, simply drop your hand or close your fist briefly, then raise the finger again.

### ⌨️ Keyboard Controls
* `ArrowUp` / `W` → Move Forward
* `ArrowDown` / `S` → Move Backward
* `ArrowLeft` / `A` → Move Left
* `ArrowRight` / `D` → Move Right

---

## 🛠️ Features

* **Smooth Voxel Jump Arc:** Features parabolic interpolation for authentic hop animations.
* **Dynamic Lighting & Shadow Mapping:** Hand-tracked directional lights follow the player to avoid clipping.
* **Visual Debug Skeleton:** A mirrored overlay canvas maps tracking joints (dots) and connecting paths (lines) over your webcam feed in real-time.
* **Procedural Infinite Generation:** Dynamic generation of roads, car speeds, and random obstacle layouts.

---

## 🚀 Getting Started

No installations or local servers are required to run this game!

1. Save the source code file as `index.html`.
2. Open `index.html` directly in any modern web browser (Chrome, Edge, or Safari recommended).
3. Grant the page permission to access your webcam when prompted.
4. Step back slightly so your hand
