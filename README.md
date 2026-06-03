# InspireRV

Interactive LED matrix project based on **CH32V003F4P6** with **MounRiver Studio**.  
This project currently includes two main modes: **RV Paint** and **RV Code**.

## Platform

- MCU: CH32V003F4P6
- Toolchain: MounRiver Studio
- Features: RV Paint / RV Code

## Overview

This project uses an 8x8 RGB LED matrix with matching button input for interactive drawing and simple RISC-V-inspired visual coding.

Two working spaces are currently implemented:

- **Coding Space** for visual instruction entry and program execution.
- **Painting Space** for direct pixel-based drawing and color editing.

## 9 Buttons Options

### Coding Space

| Button | Function |
|---|---|
| 1 | Load |
| 2 | Brightness Control |
| 3 | Save, press 9 to reset after saved |
| 4 | Return to Programming Space |
| 5 | Result |
| 6 | Run Simulation |
| 7 | Clear |
| 8 | Clear Current Page |
| 9 | To Painting Space |

### Painting Space

| Button | Function |
|---|---|
| 1 | Load |
| 2 | Brightness Control |
| 3 | Save, press 9 to reset after saved |
| 4 | Color for Foreground |
| 5 | Nil |
| 6 | Color for Background |
| 7 | To Coding Space |
| 8 | Bucket Fill |
| 9 | Clear Screen |

## Notes

- Developed for CH32V003F4P6
- Built with MounRiver Studio
- Initial public version uploaded for version control and backup
