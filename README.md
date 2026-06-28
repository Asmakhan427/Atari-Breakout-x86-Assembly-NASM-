# Atari Breakout Arcade Game

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/posts/asma-khan-28a552349_atari-breakout-arcade-game-developed-in-activity-7400651219393978369-3XwT?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFccsAoBRiHPgsTS_azhANmLFkNotHYInB4)

## Overview

**Atari Breakout Arcade Game** is a recreation of the classic Breakout game developed entirely in **x86 Assembly Language (NASM)** as part of the **Computer Organization & Assembly Language (COAL)** course at FAST National University.

---

## Features

- Interactive welcome and instruction screen
- Four rows of destructible bricks
- Paddle movement using keyboard input
- Real-time ball movement
- Brick collision detection
- Score tracking system
- Life management system
- Game Over and Win screens
- Sound effects using BIOS/DOS interrupts

---

## Technologies Used

- x86 Assembly Language (NASM)
- BIOS Interrupts
- DOS Interrupts
- Memory-Mapped Video I/O
- Text Mode Graphics

---

## Core Concepts Implemented

### Welcome Screen

The game begins with an interactive welcome screen displaying game instructions before gameplay starts.

<img width="1863" height="611" alt="image" src="https://github.com/user-attachments/assets/b55d1b62-6ccf-4cf9-ab2a-1d564bcb2959" />


---

### Gameplay

Players control a paddle to bounce the ball and destroy all bricks while preventing the ball from falling.

<img width="561" height="270" alt="image" src="https://github.com/user-attachments/assets/61cff9f3-a2b0-4a14-9f11-0ba85015fbd2" />


---

### Collision Detection

The game detects collisions between the ball, bricks, paddle, and screen boundaries to provide smooth gameplay.

<img width="562" height="352" alt="image" src="https://github.com/user-attachments/assets/7496cc5c-08bc-4c35-92b9-1c97bdcf24e1" />


---

### Score & Lives

The score increases as bricks are destroyed, while the player has a limited number of lives before the game ends.
<img width="1919" height="1001" alt="image" src="https://github.com/user-attachments/assets/5b3c063d-e296-4e58-9f67-7256db75bfce" />

---

### Game Over / Victory

The game displays dedicated Game Over and Victory screens depending on the player's performance.

<img width="565" height="228" alt="image" src="https://github.com/user-attachments/assets/5f8631d9-a4d7-43cb-b525-77a06e66b9fa" />


---

## Learning Outcomes

This project strengthened my understanding of:

- Low-level programming
- x86 Assembly Language
- BIOS and DOS interrupts
- Memory-mapped video programming
- Keyboard interrupt handling
- Collision detection algorithms
- Real-time game loop implementation
- Performance optimization under hardware constraints

---

## Project Structure

```text
Atari-Breakout/
│
├── breakout.asm
├── assets/
├── screenshots/
├── README.md
└── Makefile (optional)
```

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Atari-Breakout-Assembly.git
```

2. Assemble the source code using NASM.

```bash
nasm -f bin breakout.asm -o breakout.com
```

3. Run the program in DOSBox or another DOS-compatible emulator.

```bash
breakout.com
```
## Author

**Asma Khan**

BS Computer Science  
FAST – National University of Computer & Emerging Sciences
