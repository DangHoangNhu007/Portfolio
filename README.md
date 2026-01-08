# 🎮 [Dang Hoang Nhu] – Unity / Game Developer Portfolio

Unity Developer specializing in **gameplay programming**, **hyper-casual mechanics**, and **physics-driven systems**.  
Focused on building **playable, end-to-end prototypes** with clean architecture, strong game feel, and scalable design.

---

## 🚀 Featured Projects

---

## 🏃‍♂️ The Stack Runner – Hyper-Casual Runner

> A fast-paced hyper-casual runner featuring stacking mechanics, smooth swerve controls, and procedural level generation.

![Image](https://github.com/user-attachments/assets/c2e7ac60-22f3-4969-9307-57f0025cbdb1)

### 📌 Project Overview
This project demonstrates a complete **hyper-casual gameplay loop**: simple input, immediate feedback, and satisfying progression.  
Players collect blocks to increase height, overcome obstacles, and reach the finish line.

### 👤 Role
- Solo Developer  
- Gameplay Programming & Tools Development

### 🛠 Tech Stack
- **Engine:** Unity 6.3 LTS  
- **Language:** C#  
- **Tweening:** DOTween  
- **Architecture:** GameManager (Singleton), Component-based design  

### 🚀 Key Technical Highlights
- **Swerve Input System**  
  Implemented smooth mouse/touch input using `Mathf.Clamp` to constrain player movement and ensure consistent behavior across different screen resolutions.
- **Stacking Logic & Hierarchy Management**  
  Managed dynamic stacks using `List<Transform>`, real-time parent–child hierarchy updates, and physics-based detachment when blocks are lost.
- **Custom Level Generator Tool**  
  Developed an `EditorWindow` for procedural level creation (path length, obstacle density, prefab randomization).  
  → *Reduced level design time by approximately 80%.*
- **Game Feel & Polish**  
  DOTween-powered feedback (punch, jump), particle effects, and dynamic camera shake on collisions and failure states.

### 🎮 How to Play
- Hold & Drag: Move left/right  
- Collect blocks to grow taller  
- Avoid or break walls by sacrificing blocks  
- Reach the finish line to win

🔗 **Source:** *https://github.com/DangHoangNhu007/The-Stack-Runner-*
Demo: https://danghoangnhu.itch.io/the-stack-runner

---

## 🔫 Ricochet Shooter – Physics Puzzle Game

> A tactical puzzle shooter built around vector reflection, trajectory prediction, and cinematic slow-motion effects.

![Image](https://github.com/user-attachments/assets/ced84de7-3864-417a-ba54-2d5ee777dbc6)

### 📌 Project Overview
Ricochet Shooter showcases proficiency in **Unity Physics**, **vector mathematics**, and **raycasting**.  
Players must calculate angles and use wall reflections to eliminate enemies hidden behind obstacles.

### 👤 Role
- Solo Developer  
- Gameplay & Physics Programming

### 🛠 Tech Stack
- **Engine:** Unity 6.3 LTS  
- **Language:** C#  
- **Physics:** Unity 3D Physics  
- **Rendering:** LineRenderer (URP-ready)

### 🚀 Key Technical Highlights
- **Trajectory Prediction System**  
  Implemented a multi-step raycast solution using `Vector3.Reflect` to accurately visualize bullet bounce paths before firing.
- **Physics Materials & Collision Layers**  
  Configured custom Physic Materials (zero friction, full bounciness) and clean collision layer separation for reliable interactions.
- **Slow Motion System**  
  Controlled `Time.timeScale` and adjusted `Time.fixedDeltaTime` to preserve stable physics during dramatic slow-motion moments.
- **Destruction & Feedback**  
  Procedural shatter effects by spawning debris and applying explosion forces when enemies are eliminated.
- **Scalable Level Framework**  
  Centralized `GameManager` for win/lose states and scene transitions, supporting rapid level iteration with modular prefabs.

### 🎮 How to Play
- Drag the mouse to aim  
- Release to shoot  
- Use walls to ricochet bullets and hit enemies

🔗 **Source: https://github.com/DangHoangNhu007/Ricochet-Shooter
🔗 **Demo: https://danghoangnhu.itch.io/ricochet-shooter

---

## 🔗 Links
- GitHub: https://github.com/DangHoangNhu007
- LinkedIn: https://www.linkedin.com/in/%C4%91%E1%BA%B7ng-nhu-257b09317/

---

### 📬 Contact
Open to opportunity
