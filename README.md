# 🚀 Space Escape & Fight (2D Pygame Core Template)

A standalone, lightweight 2D action/arcade framework built in Python 3 using the **Pygame 2.5.2** library. This project showcases dynamic vector physics, automated enemy spawning cycles, live scoring mechanics, and clean application state control completely optimized for execution inside Linux environments (Ubuntu/Debian).

Developed entirely inside an **Ubuntu Terminal environment** by **quantum_exe** utilizing localized asset mapping pipelines.

---

## 🎮 Gameplay & Architectural Features
*   **Vector Object Management:** Automatically tracks, updates, and renders rapid multi-directional object trajectories framework.
*   **Dynamic UI State Rendering:** Features a real-time system overlay continuously tracking and projecting the user's current live `SCORE` values.
*   **Instantaneous State Reset Engine:** Implements a direct hardware key listener (`R` Key) to immediately clear game cache, flush runtime variable values, and trigger clean state resets upon encountering collision loops.
*   **Optimized Main Loop:** Mapped layout balancing coordinate collision checks and frame updates smoothly inside standard CPU boundaries.

---

## 🛠️ System Requirements & Environment
*   **Operating System:** Ubuntu / Debian Linux Distros preferred (Fully cross-platform compatible).
*   **Python Version:** Python 3.8 or higher.
*   **Core Engine Dependency:** Pygame 2.5.2 (SDL 2.30.0).

---

## 🚀 Installation & Execution Guide

To host, modify, or execute this codebase locally inside your terminal environment, execute the following configuration commands:

```bash
# 1. Update your local system repositories and install Python dependencies
sudo apt update
sudo apt install python3-pip python3-pygame

# 2. Verify your current Pygame framework alignment (Target version: 2.5.2)
python3 -c "import pygame; print(pygame.__version__)"

# 3. Execute the core game script directly from the project directory
python3 space_game.py
```

---

## 📂 Source Directory Architecture
```text
SpaceGame/
│
├── space_game.py       # Core execution loops, system coordinates, and keyboard controls
├── README.md           # Developer documentation and deployment layout matrix
└── requirements.txt    # Specifies raw dependency configurations (pygame==2.5.2)
```

---
*Maintained under individual developer license frameworks by **Qvantum Labs**.*
