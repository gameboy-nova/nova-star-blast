<p align="center">
<img src="https://github.com/user-attachments/assets/256d122e-e967-43d9-be1e-d65b25950184" width="300">
</p>

<h1 align="center"> 
Star Blast
</h1>

<p align="center">
Control a spaceship to dodge enemies and shoot them. Supports cooperative two-player gameplay.
</p>

---
## 🎮 Gameplay Showcase

Here’s a quick look at star blast in action:
<p align="center">
<img src="https://github.com/user-attachments/assets/0ed9bd4c-e371-4630-9228-c628b37ecccf" width="500">
</p>


## 🕹️ Controls

| Button   | Action         |
|----------|----------------|
| A_UP     | P1 Move up     |
| A_DOWN   | P1 Move down   |
| A_RIGHT  | P1 Shoot       |
| B_UP     | P2 Move up     |
| B_DOWN   | P2 Move down   |
| B_RIGHT  | P2 Shoot       |
| EXIT     | Exit game      |

---

## 🧠 Logic Overview  
Tracks player positions, enemy movement, and bullet trajectories.  
Collisions are detected between enemies, players, and bullets.

---

## 🧩 Game Loop Structure  
1. Read input  
2. Move player and bullets  
3. Move enemies  
4. Render all entities  
5. Delay  

---

## ❌ End Conditions  
- One of the players reaches the score cap  
- Exit input is received  

---

### 🧪 Notes & Improvements  
- Add power-ups and enemy wave progression for advanced gameplay
