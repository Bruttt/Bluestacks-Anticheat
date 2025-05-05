# 🛡️ Bluestacks Anti-Cheat - Memory Guard

A lightweight kernel-level anti-cheat system designed to **block memory read/write operations** targeting **Bluestacks**.  
It uploads a driver to monitor and protect the emulator from external tampering and memory hacks.

---

## ✨ Features

- 🔐 Blocks memory read/write access to Bluestacks processes  
- 🚫 Prevents memory-based cheating tools and trainers  
- 🧠 Uses a secure kernel-mode driver for deep protection  
- ⚙️ Minimal system impact with real-time process monitoring  
- 🕵️ Detects unsigned or suspicious processes automatically  

---

## 🛠️ How It Works

1. A custom driver is uploaded and loaded into the kernel.
2. The driver monitors system calls and prevents unauthorized memory access to `HD-Player.exe` (Bluestacks).
3. All suspicious or unsigned processes attempting to access memory are blocked.

---

## 📂 Project Structure
!Screenshot 2025-05-05 164255.png

