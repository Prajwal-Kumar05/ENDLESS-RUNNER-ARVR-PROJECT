# 🎮 AR/VR Endless Runner Game

<div align="center">

<img src="https://img.shields.io/badge/Engine-Unity-000000?style=for-the-badge&logo=unity&logoColor=white"/>
<img src="https://img.shields.io/badge/Language-C%23-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
<img src="https://img.shields.io/badge/Platform-AR%2FVR-FF6B6B?style=for-the-badge&logo=oculus&logoColor=white"/>
<img src="https://img.shields.io/badge/Toolkit-XR%20%7C%20VR-7B2FBE?style=for-the-badge&logo=unity&logoColor=white"/>
<img src="https://img.shields.io/badge/Type-3D%20Game-00b4d8?style=for-the-badge&logo=unrealengine&logoColor=white"/>
<img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge"/>

<br/><br/>

</div>

An immersive AR/VR endless runner game built with Unity, combining real-time gameplay mechanics, procedural environment generation, character customization, and interactive 3D environments into a single engaging experience.

---

## 🎯 Objective

Explore immersive AR/VR game development by building an interactive endless runner that combines engaging gameplay mechanics, character customization, collectible systems, and optimized real-time 3D environments.

---

## ✨ Features

### 🏃 Endless Runner Gameplay
Infinite procedurally generated tracks with continuously spawning obstacles and increasing difficulty. Speed scales dynamically as the player progresses, keeping gameplay challenging and engaging.

### 🥽 AR/VR Immersive Environment
Fully immersive AR/VR experience built with Unity's XR Toolkit. Real-time rendering and physics interactions deliver a responsive and visually rich 3D environment.

### 🪙 Coin Collection & Scoring
Collectible coins scattered across the track boost the player's score. A live scoring system tracks progress and rewards skillful play throughout each run.

### 👗 Character Customization
In-game cloth changing and character customization system lets players personalize their runner. Enhances player interaction and adds replay value through cosmetic progression.

### 🎮 Smooth Controls & Movement
Optimized player movement with fluid controls designed for AR/VR input systems. Obstacle avoidance feels natural and responsive across all supported devices.

### 🌍 Procedural Level Generation
Tracks, obstacles, and collectibles spawn dynamically at runtime — no two runs are identical. Ensures a fresh experience every playthrough.

### 🖥️ Interactive UI System
Clean in-game UI for score display, game state management (start, pause, game over), and the customization menu. Designed for ease of use in an immersive VR context.

---

## 🛠️ Tech Stack

| Layer | Tools |
|---|---|
| Game Engine | Unity |
| Language | C# |
| XR Framework | Unity XR Toolkit / VR Toolkit |
| Graphics | 3D Real-Time Rendering |
| Systems | Physics Engine, Animation System |
| Level Design | Procedural Generation |

---

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/your-username/arvr-endless-runner
```

2. **Open in Unity**
   - Open Unity Hub → Add Project → select the cloned folder
   - Recommended Unity version: `2021.3 LTS` or above

3. **Install XR Plugin**
   - Go to `Edit → Project Settings → XR Plug-in Management`
   - Enable your target platform (Oculus / OpenXR / ARCore)

4. **Run the Game**
   - Press **Play** in the Unity Editor, or build to your target AR/VR device

---

## 📁 Project Structure

```
Assets/
├── Scripts/
│   ├── PlayerController.cs      # Movement & input handling
│   ├── ObstacleSpawner.cs       # Procedural obstacle generation
│   ├── TrackGenerator.cs        # Infinite track spawning
│   ├── CoinCollector.cs         # Coin pickup & score logic
│   ├── CharacterCustomizer.cs   # Cloth / outfit system
│   └── GameManager.cs           # Game state & difficulty scaling
├── Scenes/
│   ├── MainMenu.unity
│   └── GameScene.unity
├── Prefabs/                     # Track tiles, obstacles, coins
├── Materials/                   # Character outfits & environment
└── XR/                          # XR Toolkit configuration
```

---

## 📸 Screenshots

<img width="600" height="300" alt="Screenshot 2025-05-09 121828" src="https://github.com/user-attachments/assets/fea1a858-6eb8-4867-9e4e-885e6ac92915" />
<img width="600" height="300" alt="Screenshot 2025-05-09 122005" src="https://github.com/user-attachments/assets/d4883ea8-66cb-4cb6-8fb4-237c122e72ec" />
<img width="600" height="300" alt="Screenshot 2025-05-09 121925" src="https://github.com/user-attachments/assets/eff4c34e-a03f-4fe9-839c-69ce86d3a4b9" />

---

## 📄 License

MIT License — free to use, modify, and distribute.




