# Balloon Blaster – 8086 Assembly Game

A vertical shooting game built entirely in **8086 Assembly Language** using the **emu8086** emulator.

## Controls
- ↑ / ↓ : Move player up/down  
- Spacebar : Shoot arrow  
- Enter : Start / Restart game
-Pop as many balloons as possible before 9 miss attempts! 

## Features
- Real-time input handling via BIOS interrupts (INT 16h)
- Direct video memory manipulation (Segment 0B800h)
- Simple game loop with score tracking (Hits & Misses)
- ASCII-based visual rendering for player, arrows, and balloons
- Game Over and Restart screen functionality

## Architecture
- Written in **8086 Assembly Language**
- Emulated on **emu8086** (Real Mode, 16-bit)
- Game flow controlled through modular procedures:
  - 'main_loop', 'key_pressed','render_arrow','render_loon', 'show_score', 'clear_screen', 'game_menu',' game_over'

## Tools Used

- **emu8086 Emulator**: For coding and testing
- **INT 10h, INT 16h, INT 21h**: For video control, keyboard handling, and DOS services

## Demo

![Gameplay Preview](demo.gif)

## References

- Intel 8086 Programming Manual
- [Emu8086 Documentation](http://www.emu8086.com/)
- Kip R. Irvine – Assembly Language for x86 Processors

## Team

- Kunal Routray (2341018202)  
- Samikshya Sanskruti Swain (2341019634)  
- Priti Rani Maity (2341013065)  
- Prabeen Kumar Pradhan (2341016346)  

## Final Thought

> “This project proves that even with low-level resources, high-level creativity can bring games to life.”
